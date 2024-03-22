# Model Classification of CIFAR10 dataset
## Objectives
1. Make this network: C1 C2 c3 P1 C4 C5 C6 c7 P2 C8 C9 C10 GAP c11
2. Keep the parameter count less than 50000
3. Max Epochs is 20
4. Use normalization - Group, Layer and Batch with each case achieve above 70% accuracy

## Result
### BN normalization
![Code BN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/9cd69541-b7ac-455b-9032-905817402a3c)

### GN normalization
![Code GN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/af0cf0d5-4f8b-4638-88a1-91563049ca37)

### LN normalization
![Code LN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/5258a277-bfec-4462-893f-3d6ed8081d7b)

## Performance Metrics
### BN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/1ead99ae-d55f-4aae-8275-a7f288371a71)

### GN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/9f0a9941-033f-4114-9c34-1b529dbd859b)
### LN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/ff3223b2-32b8-4615-8982-0ff3fd54b025)

## Mispredicted Image - Batch Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/35b871e3-a1c4-418c-883e-9305ce70c8ef)

## Mispredicted Image - Group Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/4e009bc4-f5f1-4f57-956c-4571d88db3f9)

## Mispredicted Image - Layer Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/ea34c9eb-4ad6-40d0-81b7-146f9ed46259)


