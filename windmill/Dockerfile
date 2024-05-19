FROM ghcr.io/windmill-labs/windmill:main

RUN mkdir -p $HOME/pw-browsers
ENV PLAYWRIGHT_BROWSERS_PATH=$HOME/pw-browsers
RUN pip install playwright
RUN playwright install
RUN playwright install-deps

CMD ["windmill"]