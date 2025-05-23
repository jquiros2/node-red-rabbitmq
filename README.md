

# source
This repo is a fork from [@breshinas/node-red-contrib-amqp](https://github.com/breshinas/node-red-contrib-amqp) 

The nodes are adapted to work with RabbitMQ and their newer Quorom type queues. You can set the additional queue options from the node configuration.

## Installation

Install via the Palette Manager or from within your node-red directory (typically `~/.node-red`) run:

```
npm i @mnn-o/node-red-rabbitmq
```

## Usage

Provides three nodes and an amqp broker config node.  
Please see the `Node Help` section from within node-red for more info

## Development

### Build the project

```
npm run build
```

### Run tests

```
npm test
```

Run coverage:

```
npm run test:cov
```

