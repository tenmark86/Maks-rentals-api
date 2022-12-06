# Maks-rentals-api

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites
- ruby 
- rails 
- git 
- bundle

### Setup

#### Open Terminal 

    git clone https://github.com/tenmark86/Maks-rentals-api.git
    cd Maks-rentals

### Install

    bundle install
    rails db:create
    rails db:migrate
    rails db:seed

### Usage

    rails server
    
### Run tests

    rspec spec/models
    rake rswag
