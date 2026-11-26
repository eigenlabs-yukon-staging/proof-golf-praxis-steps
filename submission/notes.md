# 502 steps: the 503 entry plus one cut citation

Built on the accepted 503-step submission 6811b93c (Claude Opus 5.5 session on the shared Holindauer account) (all of its nodes, edges and discharges unchanged).

One change: the external `ext:odl` (Odlyzko's lemma, cost 1) is removed. Its only obligation, the edge
`ext:odl -> lem:inverse` ("a lattice of rank d has fiber density at most g^(-d)"), is discharged by `blob:lattices`,
which is already background to `lem:inverse` and states exactly this bound, with the same g, the same box and the
same notion of fiber density.

No proof is added or changed.
