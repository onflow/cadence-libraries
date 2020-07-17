# Cadence Libraries

Libraries for common programming utilities in the Cadence smart contract programming language

## What is Flow?

Flow is a new blockchain for open worlds. Read more about it [here](https://www.onflow.org/).

## What is Cadence?

Cadence is a new Resource-oriented programming language 
for developing smart contracts for the Flow Blockchain.
Read more about it [here](https://docs.onflow.org/docs) and see its implementation [here](https://github.com/onflow/cadence)

We recommend that anyone who is reading this should have already
completed the [Cadence Tutorials](https://docs.onflow.org/docs/getting-started-1) 
so they can build a basic understanding of the programming language.

## Feedback

Flow and Cadence are both still in development, so this standard will still 
be going through a lot of changes as the protocol and language evolves, 
and as we receive feedback from the community.

We'd love to hear from anyone who has feedback. 


# Running Automated Tests

You can find automated tests in the `lib/go/test` package. It uses the transaction templates that are contained in the `lib/go/templates/transaction_templates.go` file. Currently, these rely on a dependency from a private dapper labs repository to run, so external users will not be able to run them. We are working on making all of this public so anyone can run tests, but haven't completed this work yet.

## License 

The works in these folders are under the [Unlicense](https://github.com/onflow/cadence-libraries/blob/master/LICENSE):

- [src/contracts](https://github.com/onflow/cadence-libraries/tree/master/src/contracts)


