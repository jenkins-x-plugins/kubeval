### Linux

```shell
curl -L https://github.com/jenkins-x-plugins/kubeval/releases/download/v{{.Version}}/kubeval-linux-amd64.tar.gz | tar xzv 
sudo mv kubeval /usr/local/bin
```

### macOS

```shell
curl -L  https://github.com/jenkins-x-plugins/kubeval/releases/download/v{{.Version}}/kubeval-darwin-amd64.tar.gz | tar xzv
sudo mv kubeval /usr/local/bin
```

