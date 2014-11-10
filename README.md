# whereami

This is a quick one-liner that tells you who and where you are in a color-coded format that works with [sshcd](https://github.com/fraction/sshcd). The `@` and `:` symbols are dimmed for readability, but will still work when [piped](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man2/pipe.2.html) or used in conjunction with [pbcopy](https://developer.apple.com/library/mac/documentation/darwin/reference/manpages/man1/pbcopy.1.html).

## Installation

```sh
sudo curl -Lo /usr/local/bin/whereami http://git.io/HEbojA
sudo chmod +x /usr/local/bin/whereami
```

## Usage

The default usage is pretty difficult to screw up.

```sh
whereami
```

You can get a little bit trickier though with by piping `whereami` to `pbcopy` on OS X to copy your current username, host, and path to the clipboard.

```sh
whereami | pbcopy
```

## Support

Please [open an issue](https://github.com/fraction/whereami/issues/new) for questions and concerns.

## Contributing

Fork the project, commit your changes, and [open a pull request](https://github.com/whereami/fraction/compare/).
