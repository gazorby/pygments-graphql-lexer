# Pygments GraphQL lexer

GraphQL lexer for Pygments

## Installation

    poetry install git+https://github.com/gazorby/pygments-graphql-lexer.git

## Development

### Test
Run the following command in the root directory

    python -m pygments -x -l "graphqllexer/lexer.py:GraphqlLexer" "tests/schema.graphql"
