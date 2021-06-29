# tailfollow

This bash script imitates the command `tail -f` and automatically terminates when the monitored file is no longer written to.

## Installation

Use the following command to install this software:

```bash
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to successfully complete the installation, you need to have write permissions for the installation location.

## Usage

```bash
$ tailfollow [-t sec] [-h] filename
```

### Options

+ `-t sec` Time interval between checks (default: 10).

+ `-h` Show this message.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
