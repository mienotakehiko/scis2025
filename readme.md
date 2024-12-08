# scis205

・This folder contains the needed material to reproduce our case-studies.　　<br>
・Models can be validated using the latest Tamarin prover.

---
File Description

1.&emsp;notoracle_owcca2model_verification_asymmetric-encryption.spthy <br>
2.&emsp;oracle_owcca2model_verification_asymmetric-encryption.spthy <br>
3.&emsp;oracle_owcca2model_verification_asymmetric-encryption.log <br>
4.&emsp;oracle_owcca2model_verification_asymmetric-encryption_out.spthy <br>
5.&emsp;oracle_owcca2model_verification_asymmetric-encryption_out.log <br>
6.&emsp;myoracle

---
1.&emsp;notoracle_owcca2model_verification_asymmetric-encryption.spthy <br>

  emsp;&emsp;Verification code not using oracle <br>
  emsp;&emsp;Verification results: verification does not stop <br>

2.&emsp;oracle_owcca2model_verification_asymmetric-encryption.spthy <br>

  &emsp;&emsp;Verification code using oracle <br>
  &emsp;&emsp;Verification results: oracle_owcca2model_verification_asymmetric-encryption.log <br>

3.&emsp;oracle_owcca2model_verification_asymmetric-encryption.log <br>

  &emsp;&emsp;Result of running the above file: oracle_owcca2model_verification_asymmetric-encryption.spthy <br>

4.&emsp;oracle_owcca2model_verification_asymmetric-encryption_out.spthy <br>

  &emsp;&emsp;Verification code using oracle (however, the Sender side intentionally leaked the private key to the outside model) <br>
  &emsp;&emsp;Verification results: oracle_owcca2model_verification_asymmetric-encryption_out.log <br>

5.&emsp;oracle_owcca2model_verification_asymmetric-encryption_out.log <br>

   &emsp;&emsp;Result of running the above file: oracle_owcca2model_verification_asymmetric-encryption_out.spthy <br>

6.&emsp;myoracle <br>
  &emsp;&emsp;Oracle code described in python3 <br>

---
