# Open Project ID Protocol

Open Project ID Protocol is a simple protocol to identify our porjects with useful IDs where it saves determinated description of the project.

## Motivation

At Minky always needs to create a pricing draft for our projects, and we think that our Project ID should contain a stateless representation of the basic details of such project. With this think in the mind, we invent a simple protocol to archive this goal.

### Exploring our needs

We Needs:

- Business Model Type (1 byte)

- Project Type (1 byte)

- Project Customer (4 bytes)

- Project Complexity (1 byte)

- Project Number (5 bytes)

  

Total: 12 bytes (96 bits)

`BB TT CC CC CC CC XX NN NN NN NN NN`

Example:

**0x01 0x01 0x00 0x00 0x00 0x03 0x80 0x00 0x00 0x00 0x00 0x01**

B: 0x01  `social type`

T: 0x01 `app type`

C: 0x00000003 `scharff customer`

X: 0x10 `128/256 of complexity`

N: 0x0000000001 `project number 1`

base64: `AQEAAAADEAAAAAAB`

