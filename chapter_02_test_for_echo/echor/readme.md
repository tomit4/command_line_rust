## Chapter 2: Test for Echo

Of interest in this chapter, we learned we can remove the `target` directory in
any projects we don't wish taking up disk space (i.e. we won't be working on it
for a while and are happy with just having the binary or even not). Rather than
doing this using the old `rm -rf` or `sudo rm -r` command we're so used to
using, we can simply use cargo to do so like so:

```sh
cargo clean
```
