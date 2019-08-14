# charthub.litmuschaos.io
front-end for litmus community charts.
# installation
install NPM packages
`yarn install`.
# usage
in command line run: `yarn start` to run development build
to create production build run `yarn build`. Open your browser and go to `http://localhost:3000/`

# docker
Build and tag the Docker image:
`docker build -t sample:dev .`.
Once the build is done run: `docker run -v ${PWD}:/app -v /app/node_modules -p 3001:3000 --rm sample:dev`.

Go to your browser and open: `http://172.17.0.2:3000/`