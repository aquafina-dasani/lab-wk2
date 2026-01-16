Luis G Morin - A01433302, Nick Cao - A01429602

## Part 1

![part1.png](/img/part1.png)

```bash
ssh-keygen -t ed25519 -f ~/.ssh/wkone -C "File used for lab1"
```

---

## Part 2
We connect the `wkone.pub` key to AWS as a keypair called `wkone`, and when we provision a Debian EC2 instance, we use `wkone` as the keypair for SSH.

## Part 3
