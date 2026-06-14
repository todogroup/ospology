serve:
	hugo server \
		--disableFastRender \
		--buildDrafts \
		--buildFuture \
		--ignoreCache \
		--printI18nWarnings \
		--printMemoryUsage \
		--printPathWarnings \
		--printUnusedTemplates \
		--templateMetrics \
		--templateMetricsHints \
		--gc

serve-with-pagefind:
	hugo --baseURL=/ && npx -y pagefind@1.5.2 --site public --output-subdir ../static/pagefind
	$(MAKE) serve

production-build:
	git submodule update --init --recursive
	mise exec hugo-extended@0.161.1 -- hugo \
		--minify
	npx -y pagefind@1.5.2 --site public

preview-build:
	git submodule update --init --recursive
	mise exec hugo-extended@0.161.1 -- hugo \
		--baseURL $(DEPLOY_PRIME_URL) \
		--buildDrafts \
		--buildFuture \
		--minify
	npx -y pagefind@1.5.2 --site public
