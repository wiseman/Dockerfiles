# Dockerfile for VirtualRadarServer

## Building

```
docker build -f Dockerfile -t jjwiseman/vrs .
```

## Running

```
docker run -d -p 8080:8080 -e "ADMIN_USER=wiseman" -e "ADMIN_PASSWORD=wiseman" jjwiseman/vrs
```

Then visit `http://localhost:8080/VirtualRadar/WebAdmin/Index.html`
