# Igniter

As soon as you start balancing, you install the Iginiter script:

Log in to your node

\
go to the home directory:

`cd ~`

`git clone `[`https://github.com/RooSoft/igniter.git`](https://github.com/RooSoft/igniter.git)

`cd igniter`

`nano igniter.sh`

Customize the header of the script (tip: use ringtools CLI or Web for convenience)&#x20;

After that you can then test the route (probing) with:

`./igniter.sh build`

And finally route the payment with:

`./igniter.sh send | tee fees.txt`

For more information about the whole process check also: https://github.com/RooSoft/igniter

So you only do the rebalancing act when all fees are at 0 or 1 and there are no more red lines visible with Ringtools 😉
