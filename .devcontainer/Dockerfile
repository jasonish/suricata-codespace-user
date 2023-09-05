FROM jasonish/suricata:7.0
RUN dnf -y install \
        git \
        jq \
        python3-pip && \
    python3 -m pip install suricata-language-server
