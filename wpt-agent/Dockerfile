FROM webpagetest/agent
RUN apt-get update && \
    apt-get install --yes --no-install-recommends \
            fonts-noto-cjk \
    && rm -rf /var/lib/apt/lists/*
