# cd_frontend
The FE node for the cxDocs website


## Setup

Clone the repo

build the image in docker
`sudo docker Build --name fe_node .`


run the image with port 80 open
`sudo docker run -d -p 80:80 fe_node`

You'll have to rebuild the image each time you want to make a change.
