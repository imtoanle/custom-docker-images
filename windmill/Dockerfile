FROM ghcr.io/windmill-labs/windmill:main

RUN pip install playwright
RUN playwright install
RUN playwright install-deps
RUN npx playwright install

CMD ["windmill"]