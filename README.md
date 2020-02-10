# Open Project ID Protocol

Open Project ID Protocol is a simple protocol to identify our porjects with useful IDs where it saves determinated description of the project.

## Motivation

At Minky always needs to create a pricing draft for our projects, and we think that our Project ID should contain a stateless representation of the basic details of such project. With this think in the mind, we invent a simple protocol to archive this goal.

### Exploring our needs

Needs:

- Project Number (4 bytes)
- Business Model Type (1 byte)
- Project Type (1 byte)
- Project Customer (4 bytes)
- Project Complexity (1 byte)

