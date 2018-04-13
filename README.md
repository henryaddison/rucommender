# RUCFUU
**RU**st **C**ollaborative **F**iltering **U**ser-**U**ser

Yeah, probably want a better name.

## Overview

An implementation in Rust of a collaborative filtering recommendations algorithm with a user-user similarity based on interactions with the same items.

**STATUS:** This is project I'm using to learn some Rust and to reinforce my knowledge of recommender systems.

## Getting Started

### Pre-requisites

Rust and Cargo

### Setting up

1. Fork and clone (or download)
2. `cargo build`

### Usage

#### Inputs

1. CSV linking users to items, e.g.
    ```csv
    user_id,item_id
    1,100
    1,101
    2,100
    2,102
    ```

#### Outputs

* Currently just similarities
* Eventually also recommendations

#### Examples

To spit out some similarities for a set of activities to make sure everything is working:
`cargo run < examples/dummy/activity.csv`

#### Tests

`cargo test`

## Getting involved

Err.
Fork and clone and PR?
I don't know I've not done much of this before.