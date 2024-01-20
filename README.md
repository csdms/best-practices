# best-practices-slides

Slides on CSDMS-themed best practices in scientific software development.

## presentation

Present these slides with [reveal-md](https://github.com/webpro/reveal-md) through their public Docker image:
```
git clone https://github.com/mdpiper/best-practices-slides
docker run --rm -p 1948:1948 -p 35729:35729 -v $PWD/best-practices-slides:/slides webpronl/reveal-md:latest /slides --watch
```
The service is now running at http://localhost:1948.
