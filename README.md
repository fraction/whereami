# whereami

This is a quick one-liner that tells you who and where you are in a color-coded format that works with [sshcd](https://github.com/christianbundy/sshcd). The `@` and `:` symbols are dimmed for readability, but will still work when [piped](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man2/pipe.2.html) or used in conjunction with [pbcopy](https://developer.apple.com/library/mac/documentation/darwin/reference/manpages/man1/pbcopy.1.html).

![](http://i.imgur.com/P4MYPwH.png)

## Installation

```sh
sudo curl -o /usr/local/bin/whereami https://raw.githubusercontent.com/christianbundy/whereami/master/whereami
```

## Usage

The default usage is pretty difficult to screw up.

```sh
whereami
```

You can get a little bit trickier though with `pbcopy`. To copy your current path (remember, it's an SSH URI scheme!) just pipe to pbcopy.

```sh
whereami | pbcopy
```

## Support

Please [open an issue](https://github.com/christianbundy/whereami/issues/new) for questions and concerns.

## Contributing

Fork the project, commit your changes, and [open a pull request](https://github.com/christianbundy/whereami/compare/).
