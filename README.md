# ansible
Used to setup coding env on ubuntu machine
## To test in Docker
1. `docker build . -t ansible-test`
2. `docker run ansible-test`

## To run
1. `apt install ansible`
2. `apt install git`
3. `ansible-playbook local.yml --verbose -K`
