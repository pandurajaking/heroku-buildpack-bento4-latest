# heroku-buildpack-bento4-latest

[![CircleCI](https://circleci.com/gh/DigitalSapphire/heroku-buildpack-bento4-latest/tree/master.svg?style=svg)](https://circleci.com/gh/DigitalSapphire/heroku-buildpack-bento4-latest/tree/master)

A Heroku buildpack for ffmpeg that always downloads the latest [static build](https://www.bento4.com).
Unlike other build packs, I never compile anything.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/DigitalSapphire/heroku-buildpack-bento4-latest.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/DigitalSapphire/heroku-buildpack-bento4-latest
```