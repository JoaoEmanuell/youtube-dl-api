# Youtube-dl api

A web API for [youtube-dl](https://github.com/ytdl-org/youtube-dl), used to extract direct links for YouTube videos and playlists.

[Read the docs](./docs/README.md)

# Getting Started

Clone the repository:

```
git clone https://github.com/JoaoEmanuell/youtube-dl-api.git
```

## Python

**Requirements**

```
python => 3.11
```

Install the dependencies:

```
pip install -r requirements.txt
```

Run the project:

```
flask run --host 0.0.0.0 --port 8080
```

## Docker

```
Docker => 24
docker-compose => 1.29
```

Build:

```
docker-compose build
```

Run the container:

```
docker-compose up
```