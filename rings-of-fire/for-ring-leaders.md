# For ring leaders

The steps to follow after everyone has opened the channel to their clockwise neighbour:

1.  Create a poll to decide on a date and time to balance. Keep in mind that people might be in different time-zones and have a day job.&#x20;

    Pro-tip: Use the [World Clock-Meeting Planner](https://www.timeanddate.com/worldclock/meeting.html) to check suitable times.
2. Check out the tools to monitor and balance the ring:
   1. For monitoring the channels and fees you can choose between [ringtools](https://github.com/StijnBTC/Ringtools) (CLI) or [ringtools-web](https://ringtools.djuri.nl) (GUI)
   2. For balancing we use [RooSoft's Igniter](https://github.com/RooSoft/igniter)
3. Depending on your choice of tools, the masters of ceremony will provide you with the necessary documentation.&#x20;
4.  When the balancing act takes place, everyone lowers their fee so the ringleader can send a transaction through the entire ring.&#x20;

    _Sometimes gossip prevents zero-cost routing of this transaction, since the ringleader can see which node collected possible fees it is appreciated if you pay the ringleader back those fees._
5. If everyone set their fees low, and this is shown in ringtools the ringleader builds and sends the transaction.
6. Congratulations, everyone should now have nicely balanced channels.
