FROM nvcr.io/nvidia/pytorch:25.01-py3
COPY --from=ghcr.io/astral-sh/uv:0.9.29-debian-slim /uv /uvx /bin/
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt