# Model Classification of CIFAR10 dataset
## Objectives
1. Make this network: C1 C2 c3 P1 C4 C5 C6 c7 P2 C8 C9 C10 GAP c11
2. Keep the parameter count less than 50000
3. Max Epochs is 20
4. Use normalization - Group, Layer and Batch with each case achieve above 70% accuracy

## Result
### BN normalization
![Code BN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/3335c9ae-0d40-41d6-be8c-1881d8a32c45)

### GN normalization
![Code GN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/af0cf0d5-4f8b-4638-88a1-91563049ca37)

### LN normalization
![Code LN](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/5258a277-bfec-4462-893f-3d6ed8081d7b)

## Performance Metrics
### BN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/2a594c0c-c778-4bdc-b41a-bd030e16a707)


### GN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/9f0a9941-033f-4114-9c34-1b529dbd859b)


### LN normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/ff3223b2-32b8-4615-8982-0ff3fd54b025)

## Mispredicted Image - Batch Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/b32cfd49-d73f-4344-bf6b-93430908da74)

## Mispredicted Image - Group Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/4e009bc4-f5f1-4f57-956c-4571d88db3f9)

## Mispredicted Image - Layer Normalization
![image](https://github.com/PRIYE/ERAV2_Session8/assets/7592375/ea34c9eb-4ad6-40d0-81b7-146f9ed46259)


