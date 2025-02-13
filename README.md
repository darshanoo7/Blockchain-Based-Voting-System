# Blockchain-Based-Voting-System

#### Abstract
This paper support the open source Blockchain technology to propose a design for a new electronic voting system that could be used in local or national elections.

#### Introduction
An e-Voting system has to have heightened security in order make sure it is available to voters but protected against outside influences changing votes from being cast, or keep a voter’s ballot from being tampered with. Many electronic voting systems rely on to hide the identity of voters. However, this technique does not provide total anonymity or integrity since many intelligence agencies around the world control different parts of the Internet which can allow them to identify or intercept votes. 

#### Blockchain
Blockchain was first introduced by Satoshi Nakamoto (a pseudonym), who proposed a peer-to-peer payment system that allows cash transactions through the Internet without relying on trust or the need for a financial institution.

Blockchain is an ordered data structure that contains blocks of transactions. Each block in the chain is linked to the previous block in the chain. The first block in the chain is referred to as the foundation of the stack. Each new block created gets layered on top of the previous block to form a stack called a Blockchain. 


All of the magic lies in the way this data is stored and added to the blockchain. A blockchain is essentially a linked-list containing ordered-data, with some constraints like below;

* Blocks can't be modified once added; in other words, it is "append-only."
* There are specific rules for appending data to it.
* It's distributed in architecture.
* Enforcing these constraints yields some highly desirable characteristics:

* Immutability and durability of data
* No single point of control or failure
* A verifiable audit trail of the order in which data was added




## Instructions to run the application

Clone the project,

```sh
$ git clone https://github.com/adhikarir/E-voting-system-using-blockchain-and-python.git
```

Install the dependencies,

```sh
$ cd E-voting-system-using-blockchain-and-python
$ pip install -r requirements.txt
```

Start a blockchain node server,

```sh
# Windows users can follow this: https://flask.palletsprojects.com/en/1.1.x/cli/#application-discovery
$ export FLASK_APP=service.py
$ flask run --port 8000
or
python3 -m flask run --port 8000
```

One instance of our blockchain node is now up and running at port 8000.


Run the application on a different terminal session,

```sh
$ python app.py
```

The application should be up and running at [http://localhost:5000](http://localhost:5000).
