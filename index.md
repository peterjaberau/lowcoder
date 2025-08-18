```bash

# docker backend
# https://docs.lowcoder.cloud/lowcoder-documentation/lowcoder-extension/opensource-contribution
docker run -d --name lowcoder -p 3000:3000 -v "$PWD/stacks:/lowcoder-stacks" lowcoderorg/lowcoder-ce


# node 20
volta pin node@20

# start frontend dev
cd client
yarn install
LOWCODER_API_SERVICE_URL=http://localhost:3000 yarn start




```
