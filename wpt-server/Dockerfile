FROM webpagetest/server
RUN apt-get update && \
    apt-get install --yes --no-install-recommends \
            php-apc \
    && apt-get install --yes \
               python-dev \
               python-pip
    && rm -rf /var/lib/apt/lists/*

RUN pip install pyssim
