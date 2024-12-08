README
scis205
・This folder contains the needed material to reproduce our case-studies.　
・Models can be validated using the latest Tamarin prover.

File Description

1. notoracle_owcca2model_verification_asymmetric-encryption.spthy
2. oracle_owcca2model_verification_asymmetric-encryption.spthy
3. oracle_owcca2model_verification_asymmetric-encryption.log
4. oracle_owcca2model_verification_asymmetric-encryption_out.spthy
5. oracle_owcca2model_verification_asymmetric-encryption_out.log
6. myoracle

1. notoracle_owcca2model_verification_asymmetric-encryption.spthy

  Verification code not using oracle
  Verification results: verification does not stop

2. oracle_owcca2model_verification_asymmetric-encryption.spthy

  Verification code using oracle
  Verification results: oracle_owcca2model_verification_asymmetric-encryption.log

3. oracle_owcca2model_verification_asymmetric-encryption.log

  Result of running the above file: oracle_owcca2model_verification_asymmetric-encryption.spthy

4. oracle_owcca2model_verification_asymmetric-encryption_out.spthy

  Verification code using oracle (however, the Sender side intentionally leaked the private key to the outside model)
  Verification results: oracle_owcca2model_verification_asymmetric-encryption_out.log

5. oracle_owcca2model_verification_asymmetric-encryption_out.log

   Result of running the above file: oracle_owcca2model_verification_asymmetric-encryption_out.spthy

6. myoracle
  Oracle code described in python3
