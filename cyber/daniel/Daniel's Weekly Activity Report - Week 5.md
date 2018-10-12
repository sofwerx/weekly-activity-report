# Daniels's Weekly Activity Report - Week 5  (Sep. 27, 2018)
### Legend
- [Intent](#intent)
- [Meetings](#meetings)
- [TODO](#TODO)
- [References](#references)

### Big Updates

-  Kuala Lumpar city export reached over 600,000 lines of data including coordinates. After the coordinates were stripped out, they were reversed geocoded into addresses, if they returned as being in Kuala Lumpar, they were saved. The rest were discard. 50,000 coordinates in Kuala Lumpar are now left and are returning street view images.
-  Many more domecameras and long cameras collected, soon to be annotated and trained on the cluster


### Intent

The intent behind my project is to download every single street view image in a given city. After these are downloaded, object recognition will take place and identify stuff like power transformers, security cameras etc. The purpose is to be able to quickly and automatically map out an entire cities power grid or security camera locations


### Meetings
 - Weekly Friday Review meeting with David
 - Weekly Friday meeting with team

### TODO

- Setup docker file on cluster
- Annotate and train collected images
- Have tensorflow send command when object is detected

### References
- Extract coordinates on a large areas: extract.bbbike.org
- Open source mapping tool: https://www.openstreetmap.org
- Relevant article: https://arxiv.org/pdf/1702.06683v2.pdf
