# data-engineering-zoomcamp
Data Engineering Zoomcamp - 2026 Cohort

docker run -it \
    --rm \
    -v $(pwd)/test:/app/test \
    --entrypoint=bash \
    python:3.9.16-slim