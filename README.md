```
sudo apt update
sudo apt install -y nodejs npm
sudo npm install n -g
sudo n stable
sudo apt purge -y nodejs npm
sudo apt autoremove -y
node -v
npm -v
```

```
npx create-react-app amplifyapp
cd amplifyapp
npm start
```

```
sudo npm install -g @aws-amplify/cli
```

```
amplify configure
```

```~/.aws/config
[profile amplify-dev]
credential_process = aws configure export-credentials --profile lm-dev-compute
region = ap-northeast-1
```

aws configure export-credentials --profile lm-dev-compute

amplify pull --appId d2c99zlnjqxo7u --envName staging

```
npm install aws-amplify @aws-amplify/ui-react
```

```
amplify add auth
```
