# best-practices

Slides on CSDMS-themed best practices in scientific software development.

## presentation

Present these slides with [reveal-md](https://github.com/webpro/reveal-md) through their public Docker image:
```
git clone https://github.com/mdpiper/best-practices
docker run --rm -p 1948:1948 -p 35729:35729 -v $PWD/best-practices:/slides webpronl/reveal-md:latest /slides --watch
```
The service is now running at http://localhost:1948.
