# whereami

This is a quick one-liner that tells you who and where you are in a color-coded format that doubles as an SSH URI scheme. The `@` and `:` symbols are dimmed for readability, but will still appear when [piped](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man2/pipe.2.html) or used in conjunction with [pbcopy](https://developer.apple.com/library/mac/documentation/darwin/reference/manpages/man1/pbcopy.1.html).

![](http://i.imgur.com/P4MYPwH.png)

## installation

```sh
git clone https://github.com/christianbundy/whereami.git && cd whereami
sudo cp whereami /usr/local/bin
```

## usage

The default usage is pretty difficult to screw up.

```sh
whereami
```

You can get a little bit trickier though with `pbcopy`. To copy your current path (remember, it's an SSH URI scheme!) just pipe to pbcopy.

```sh
whereami | pbcopy
```
