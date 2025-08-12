
## How to Build & Run

1. Clone this repo.

```
$ git clone https://github.com/MICOTYN-PATCH/mdc-chat.git
```

2. Navigate into the project folder.

```
$ cd chat
```

3. Download all dependencies.

```
$ go mod download
```

4. Verify dependency checksums to ensure nothing fishy is going on.

```
$ go mod verify
```

5. Build the binary.

```
$ go build -o chat
```

6. Run the binary.

```
$ ./chat
```

config -

If a `settings.cfg` file doesn't exist, one will be created on first run. Modify it to your liking and run the binary again when done.
