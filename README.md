# How to Build
`docker build -t simple-flask .`

# Run
Map machine's port 4000 to the container's `EXPOSE`d port 80 using `-p`.

`docker run -p 4000:80 simple-flask`

You can also use the `curl` command to view the same content.

`curl http://localhost:4000`