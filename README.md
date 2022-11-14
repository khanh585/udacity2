### Project Title - Deploy a high-availability web app using CloudFormation

Udacity Project 2 - KhanhTD

## Project File Structure

- `diagram.jpg`: This describes the architecture diagram.
- `network-parameters.json`: Parameters file for network Cloudformation Stack.
- `network.yml`: CloudFormation template to create network resources.
- `server-parameters.json`: Parameters file for servers Cloudformation Stack.
- `servers.yml`: CloudFormation template to create servers.
- `create.sh`: Script to create CloudFormation Stack.
- `update.sh`: Script to update CloudFormation Stack.
- `delete.sh`: Script to delete CloudFormation Stack.

## Project Setup

- Create networking resources using cloud formation template.

```
$ ./create.sh udacity-network-khanhtd network.yml network-parameters.json
```

- Create servers.

```
$ ./create.sh udacity-server-khanhtd servers.yml server-parameters.json

```

- URL to verify my work is running.

[URL to verify](http://udaci-webap-1bmr3rognpoh5-1300796436.us-west-2.elb.amazonaws.com/)
