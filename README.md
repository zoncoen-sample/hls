# hls

Apple HTTP Live Streaming example.

## Requirements

- ffmpeg
- Safari

## How to use

Transcode to hls files.

```console
$ git clone https://github.com/zoncoen-sample/hls.git
$ cd hls
$ ./bin/transcode2hls {in_movie_file}
```

Start local http server.

```console
$ ./bin/httpd
```

Open <http://localhost:5000/index.html> in your Safari.
