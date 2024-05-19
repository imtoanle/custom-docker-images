FROM ghcr.io/windmill-labs/windmill:main

RUN npm install -g playwright@latest
RUN npx playwright install-deps chromium

CMD ["windmill"]