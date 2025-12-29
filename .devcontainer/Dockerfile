# .devcontainer/Dockerfile

# Microsoft公式のPython DevContainerイメージを使用
FROM mcr.microsoft.com/devcontainers/python:3.11

# 追加ツール（必要に応じて）
USER vscode
RUN curl -LsSf https://astral.sh/uv/install.sh | sh
ENV PATH="/home/vscode/.local/bin:${PATH}"

# 作業ディレクトリの設定
WORKDIR /home/vscode/python

# コンテナを起動したままにする
CMD ["sleep", "infinity"]