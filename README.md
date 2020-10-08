# heroku-buildpack-ffmpeg-stable

A Heroku buildpack for ffmpeg that always downloads a stable, tested ffmpeg build from ffmpeg repo, previously compiled. 
Check CHANGELOG.txt to see what version is currently compiled.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/matovolador/heroku-buildpack-ffmpeg-latest.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/matovolador/heroku-buildpack-ffmpeg-latest.git
```
