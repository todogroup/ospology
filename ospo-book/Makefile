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
	hugo --baseURL=/ && npx -y pagefind --site public --output-subdir ../static/pagefind
	$(MAKE) serve

production-build:
	git submodule update --init --recursive
	hugo \
		--minify
	npx -y pagefind --site public

preview-build:
	git submodule update --init --recursive
	hugo \
		--baseURL $(DEPLOY_PRIME_URL) \
		--buildDrafts \
		--buildFuture \
		--minify
	npx -y pagefind --site public
