# National Green Infrastructure Facility

[![Tests](https://github.com/fmcclean/ngif/workflows/Tests/badge.svg)](https://github.com/fmcclean/ngif/actions)

Plotly Dash app to visualise and download NGIF sensor data

## Usage
`docker run -p 80:5000 --env MONGO_URI=mongodb://username:password@hostname:27017/database?authSource=admin --env GUNICORN_CMD_ARGS="--bind=0.0.0.0:5000" --name ngif fmcclean/ngif`

## Dependencies
`pip install -r requirements.txt`

## Tests
`python -m unittest`
