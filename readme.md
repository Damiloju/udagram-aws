# Udagram

A Cloudformation project for udacity cloud devops program.

## Step 1

### To create our infrastructure via cloud formation

Run ourinfra.yml
`helpers/create.sh udagram ourinfra.yml ourinfra-params.json`

## Step 2

### To create our bastion servers via cloud formation

Run bastion-server.yml
`helpers/create.sh udagram bastion-servers.yml bastion-servers-params.json`

## Step 3

### To create our application servers via cloud formation

Run application-servers.yml
`helpers/create.sh udagram application-servers.yml application-servers-params.json`

## Updating a Stack

Run `helpers/update.sh udagram ourinfra.yml ourinfra-params.json`

## Deleting a Stack

Run `helpers/delete.sh udagram`
