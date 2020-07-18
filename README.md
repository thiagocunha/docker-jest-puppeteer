# Docker Jest + Puppeteer

A Node + Jest + Puppeteer base image for running End to End tests using Puppeteer. 

## Versions

See the list of [Docker Hub tags](https://hub.docker.com/r/thiagochierici/docker-jest-puppeteer) for Puppeteer versions available.

## Example

See the [example directory](example) for a complete Docker Compose example, showing how to run Puppeteer against a linked Docker Compose web service.

## Releasing

1. Create a new release on GitHub. The image is tagged with the same version as Puppeteer.
2. Docker Hub automatically builds images for the tag.
3. There is no step 3.
