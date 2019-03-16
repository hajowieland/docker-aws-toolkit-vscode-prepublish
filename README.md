# docker-aws-toolkit-vscode-prepublish
Docker container to compile prepublished version of aws-toolkit for Visual Studio Code ("vscode")


Dockerfile from https://github.com/aws/aws-toolkit-vscode



To run, execute the following commands:

Clone the [aws-toolkit-vscode](https://github.com/aws/aws-toolkit-vscode) repository:
`git clone https://github.com/aws/aws-toolkit-vscode.git`

Run the Docker container and mount the current directory (the aws-toolkit-vscode repo) inside:
`docker run -it -v $(pwd):/code hajowieland/aws-toolkit-vscode-prepublish`


-> Outputs vscode extension to current directory
