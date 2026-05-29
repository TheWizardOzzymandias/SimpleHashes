# SimpleHashes
Simple Python Tools to Generate and Crack Hashes with Basic Algorithms

# Hash Tools

Simple Python tools built while learning cybersecurity and Python scripting.

## Included Scripts

### `hashgen.py`

Generates hashes for a user-provided string using algorithms available in Python's `hashlib` library.

Features:

* Supports multiple hashing algorithms
* Automatically iterates through available algorithms
* Handles SHAKE hash output lengths

### `hashcrack.py`

Attempts dictionary attacks against hashes using a provided wordlist.

Features:

* Tests multiple hashing algorithms
* Reads password candidates from a wordlist
* Supports SHAKE algorithms
* Detects matching cleartext passwords

---

## Requirements

* Python 3

---

## Usage

Generate hashes:

```bash
python3 hashgen.py
```

Crack hashes:

```bash
python3 hashcrack.py
```

---

## Example

Example MD5 hash:

```text
5f4dcc3b5aa765d61d8327deb882cf99
```

Example wordlist path:

```text
./wordlists/rockyou.txt
```

---

## Notes

These tools were created for educational purposes while learning:

* Python scripting
* Hashing algorithms
* Dictionary attacks
* File handling
* Basic cybersecurity concepts
