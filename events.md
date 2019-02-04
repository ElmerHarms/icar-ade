This page gives an overview of the different events that we are targeting, their state regarding standardization, as well as the source and target companies that produce or consume these events. The milestone gives an indication of the priority of creating that event.

Also noted is if we would like to have the event pushed (whole message is pushed), notified (clients are notified of a change who can then pull) or pulled (client asks for latest state at initiative of the client).

Event | Description | Standard Status |Source | Source Status | Target | Target Status | Push/Pull | Milestone
--- | --- | --- | --- | --- | --- | --- | --- | --- |
milking-visits ||| lely | p2p | crv | p2p | push | 1
milking-lab-results |ijk data?|| crv | crv->lely | lely | crv->lely | pull |1
weights ||| lely, gallagher | p2p | crv, bms | p2p | pull |1
teat-coordinates ||| lely | p2p | crv, bms | p2p | pull |1
herd-list(-movements) (generic) ||| lely, crv | crv->lely | lely, crv | crv->lely | notify, pull | 2
herd-list-movements (I&R, births) ||| lely, bms, crv, rvo | lely->crv->rvo | lely, bms, crv, rvo | lely->crv->rvo | notify, pull |2
herd-list-movements (I&R, deaths) ||| lely, bms, crv, rvo | lely->crv->rvo | lely, bms, crv, rvo | lely->crv->rvo | notify, pull |2
herd-list-movements (I&R, arrivals) ||| lely, bms, crv, rvo | lely->crv->rvo | lely, bms, crv, rvo | lely->crv->rvo | notify, pull |2
herd-list-movements (I&R, departures) ||| lely, bms, crv, rvo | lely->crv->rvo | lely, bms, crv, rvo | lely->crv->rvo | notify, pull |2
heat-report | actual report || bms, scr, nedap, crv-vm... | misc | crv, lely, bms |  | push, notify, pull |3
heat-activities | graph data  || scr, nedap | misc | crv, lely, bms |  | push, notify, pull |3
health-report | actual report|| bms, scr, nedap, crv-vm... | misc | crv, lely, bms |  | push, notify, pull |3
health-activities | actual report|| scr, nedap | misc | crv, lely, bms |  | push, notify, pull |3
treatments | medical treatments, medicines, .. || lely,crv,bms | - | lely,crv,bms | - | push, notify, pull |3
inseminations ||| crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
drying-offs ||| crv, lely, bms, ... |  | crv, lely, bms, ... |  | notify, pull |3
pregnancy-checks ||| crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
abortions ||| crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
parturitions | geboorteverloop, bijzonderheden, verlossingsdata || crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
natural-services ||| crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
keep-open ||| crv, lely, bms | crv<->lely | crv, lely, bms | crv<->lely | pull |3
mpr-results | || crv | crv->lely | lely | crv->lely, bms | pull |4
