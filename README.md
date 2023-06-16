# Seqsy

Seqsy is a permissionless sequencer network.

Anyone can join by staking and specifying the rollups they intend to sequence.
The Seqsy contracts will randomly select a sequencer for every rollup. That
sequencer is then be responsible for publishing a block for that rollup. The
other sequencers must then vote on the block. If a block passes the required
voting quorum then it is considered final for the purpose of rollup derivation
(the block can still be rejected if it does not satisfy the rollup validity
rules).
