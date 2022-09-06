# Installation

    $ pip3 install grpcio-tools
    $ python3 -m grpc_tools.protoc -I .. --python_out=. --grpc_python_out=. ../storage.proto ../task.proto

# Usage

    $ python3 task.py --token "<access_token>" --task-id "<id>" [--cancel | --wait <out>]
