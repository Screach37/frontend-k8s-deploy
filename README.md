In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm run build`

Builds the app for production to the `build` folder.\

### `Docker`

docker build -t repo/image_name:version .

('.' signifies the Dockerfile to be used from the current directory)

### `Kubernetes`

minikube start \
kubectl apply -f frontEndDeploy.yml \
kubectl apply -f frontEndSvc.yml \
kubectl get pods -ow wide
