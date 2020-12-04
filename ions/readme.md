

# dev1-mg.model

trained with P2Rank commit 64be847 with command:

```sh
./prank.sh traineval -c config/ions/ions-rdk-c1 -out_subdir DEC -l dev1 \
    -t 2020-10/mg-christos.ds -e 2020-10/mg-christos.ds \
    -loop 1 \
    -rf_trees 200 \
    -rf_bagsize 15 \
    -rf_depth 0 \
    -tessellation 2 \
    -train_tessellation 2 \
    -train_tessellation_negatives 1 \
    -delete_models 0
```

# dev1-zn.model

trained with P2Rank commit 64be847 with command:

```sh
./prank.sh traineval -c config/ions/ions-rdk-c1 -out_subdir DEC -l dev1 \
    -t 2020-10/zn-christos.ds -e 2020-10/zn-christos.ds \
    -loop 1 \
    -rf_trees 200 \
    -rf_bagsize 15 \
    -rf_depth 0 \
    -tessellation 2 \
    -train_tessellation 2 \
    -train_tessellation_negatives 1 \
    -delete_models 0
```