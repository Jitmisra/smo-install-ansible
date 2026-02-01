```
NAME                                                READY   STATUS                       RESTARTS        AGE
a1-sim-osc-0-5b68986f57-4s995                       1/1     Running                      0               12h
a1-sim-osc-1-795d9cc9cb-lmgbw                       1/1     Running                      0               12h
a1-sim-std-0-7cdcb7cfd4-2n84g                       1/1     Running                      0               12h
a1-sim-std-1-75fd6b4fc9-cl48q                       1/1     Running                      0               12h
a1-sim-std2-0-74c7ff7b59-7rgxg                      1/1     Running                      0               12h
a1-sim-std2-1-7568964db6-xh2d6                      1/1     Running                      0               12h
a1controller-5d4f57c4db-cc2bq                       0/1     Running                      132 (4m ago)    12h
a1controller-db-546cc66cfc-znwkv                    1/1     Running                      0               12h
capifcore-5888444d7c-9ppcf                          1/1     Running                      0               12h
controlpanel-5c8bbb56cf-srnsl                       0/1     CrashLoopBackOff             156 (27s ago)   12h
dmaapadapterservice-0                               1/1     Running                      0               12h
dmeparticipant-689bb796d7-g2s54                     0/1     CreateContainerConfigError   0               12h
informationservice-0                                0/1     Pending                      0               12h
mariadb-galera-0                                    1/1     Running                      0               43h
nonrtricgateway-54f77c4b94-g9hqq                    1/1     Running                      0               12h
onap-dcae-ves-collector-546c98c765-xx7d9            1/2     CreateContainerConfigError   2 (16h ago)     43h
onap-policy-apex-pdp-6b6cc88649-bgt98               0/1     ContainerStatusUnknown       1               29h
onap-policy-apex-pdp-6b6cc88649-d5484               1/1     Running                      0               16h
onap-policy-apex-pdp-6b6cc88649-w8x8p               0/1     Error                        0               41h
onap-policy-api-85d85ccf84-86v64                    0/1     Error                        1               43h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-445j8    0/1     Error                        0               41h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-77pqn    1/1     Running                      0               16h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-clfb7    0/1     ContainerStatusUnknown       1               37h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-fnggn    0/1     Error                        0               33h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-gngw4    0/1     ContainerStatusUnknown       1               26h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-vl99v    0/1     Error                        0               23h
onap-policy-clamp-ac-a1pms-ppnt-7bd7f4fccf-xgn9v    0/1     Error                        0               30h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-2s57t     0/1     Error                        0               33h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-982b7     0/1     Error                        0               25h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-cb9nw     0/1     Error                        0               29h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-fssdj     0/1     Error                        0               41h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-nx7v8     1/1     Running                      0               16h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-qwqn7     0/1     Error                        0               37h
onap-policy-clamp-ac-http-ppnt-6c5b54c6d8-tnvvf     0/1     Error                        0               22h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-26hhz      0/1     ContainerStatusUnknown       1               22h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-b5mn8      0/1     Error                        0               33h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-ggww8      0/1     Error                        0               37h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-jk6l2      0/1     Error                        0               41h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-pc9hn      0/1     ContainerStatusUnknown       1               26h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-q82hb      1/1     Running                      0               16h
onap-policy-clamp-ac-k8s-ppnt-59d486fcd5-smqsz      0/1     Error                        0               29h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-4rx8q   0/1     ContainerStatusUnknown       1               23h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-7vj2k   0/1     Error                        0               34h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-cqt2g   0/1     ContainerStatusUnknown       1               37h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-jccks   1/1     Running                      0               16h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-mtd88   0/1     ContainerStatusUnknown       1               41h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-x79jb   0/1     Error                        0               26h
onap-policy-clamp-ac-kserve-ppnt-5965cc6875-xvfqs   0/1     Error                        0               30h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-8svn6        1/1     Running                      0               16h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-r2rl9        0/1     Error                        0               29h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-sllbh        0/1     Error                        0               41h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-trcss        0/1     Error                        0               37h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-w75h5        0/1     Error                        0               25h
onap-policy-clamp-ac-pf-ppnt-fdc7c69f7-wr42x        0/1     Error                        0               33h
onap-policy-clamp-runtime-acm-59467c7b9c-bxlzx      0/1     Error                        0               30h
onap-policy-clamp-runtime-acm-59467c7b9c-jtfck      0/1     Init:0/2                     98 (89s ago)    16h
onap-policy-clamp-runtime-acm-59467c7b9c-lqzj4      0/1     ContainerStatusUnknown       1               22h
onap-policy-clamp-runtime-acm-59467c7b9c-qrrzw      0/1     Error                        0               41h
onap-policy-pap-795d67f6b5-2wk85                    0/1     Error                        0               36h
onap-policy-pap-795d67f6b5-ggw8g                    0/1     ContainerStatusUnknown       1               23h
onap-policy-pap-795d67f6b5-hxvdd                    0/1     Error                        0               28h
onap-policy-pap-795d67f6b5-stlr6                    0/1     Init:0/2                     98              16h
onap-policy-pap-795d67f6b5-w6wlx                    0/1     ContainerStatusUnknown       1               32h
onap-policy-pap-795d67f6b5-xl4fp                    0/1     ContainerStatusUnknown       1               41h
onap-policy-postgres-primary-f76cb64c-694nr         0/1     Running                      0               43h
onap-policy-postgres-replica-6887f9856f-2pdbg       0/1     Running                      1 (43h ago)     43h
onap-postgres-primary-66c8dff577-kp9wc              0/1     Running                      0               43h
onap-postgres-replica-86b64c8455-vxs8p              0/1     Running                      0               43h
onap-strimzi-kafka-bridge-857dff6bdd-jpp2g          1/1     Running                      8 (16h ago)     43h
onap-strimzi-onap-strimzi-broker-0                  0/1     Terminating                  0               43h
onap-strimzi-onap-strimzi-controller-1              1/1     Terminating                  0               43h
policymanagementservice-0                           0/1     Pending                      0               12h
rappmanager-0                                       1/1     Running                      0               12h
servicemanager-57f8f956bd-vmlzc                     1/1     Running                      0               12h
topology-77d7d49589-qv94m                           1/1     Running                      0               12h
```
