# Fully-Homomorphic-Encryption-Over-Integers

Author: Amandeep Kaur

# Design and Development of Fully Homomorphic Encryption (FHE) IP Core

## Introduction

Fully Homomorphic Encryption (FHE) is an innovative solution in cryptographic research, enabling computations on encrypted data without decryption. This project focuses on developing an FHE IP Core using FPGA technology, specifically leveraging the CMNT (Coron-Mandal-Naccache-Tibouchi) and CNT algorithms, along with Fast Fourier Transform (FFT) techniques to enhance efficiency and scalability.

## Motivation

In today's data-driven world, the need for secure computation on sensitive data is paramount. Traditional encryption schemes require decryption before performing computations, exposing data to potential security risks. FHE offers a significant tool for scenarios where data privacy is critical, allowing computations to be performed directly on encrypted data without compromising privacy.

## Objectives

The project aims to:

1. Implement FHE techniques for secure computation on encrypted data.
2. Overcome limitations of traditional encryption by enabling direct computations on encrypted data.
3. Design and develop efficient algorithms and architectures for FHE operations using FPGA technology.
4. Contribute to the advancement of secure computation techniques in various domains such as healthcare, finance, and cloud computing.

## Problem Statement

The project addresses the challenge of performing secure computations on sensitive data while preserving privacy and confidentiality. By utilizing FHE, the solution aims to eliminate the need for decryption before computation, thereby maintaining data security throughout the process.

## System Design and Architecture

The project involves designing custom algorithms for key generation, encryption, and decryption using CMNT and FFT. The implementation aims to reduce computational complexity and improve the efficiency of FHE operations. The architecture is developed to handle arithmetic operations on encrypted integers, leveraging FPGA technology for optimized performance.

## Hardware Used

- FPGA: The project utilizes FPGA technology to implement the FHE IP Core, enabling efficient and scalable computation on encrypted data.

## Scripts for Encryption Algorithms

- CMNT Scheme: Scripts are prepared for implementing the CMNT scheme, focusing on encryption, decryption, and key generation processes.
- CNT Scheme: The project also compares the CMNT scheme with the CNT scheme, evaluating performance differences in terms of key size and computation time.

## Results and Analysis

The project showcases the efficiency and practicality of the proposed FHE system, with evaluations based on computation time, memory utilization, and scalability. The results demonstrate the system's suitability for real-world applications where privacy-preserving computation is crucial.

## Future Scope

The project opens up possibilities for secure data processing in applications such as secure data outsourcing, privacy-preserving machine learning, and secure cloud computing. Future research areas include exploring the integration of the FHE IP Core with emerging technologies such as blockchain, edge computing, and IoT devices 【13:2†source】【13:3†source】【13:5†source】.

## References

1. Gentry, C.: A fully homomorphic encryption scheme. Ph.D. thesis, Stanford University, 2009.
2. Gentry, C.: Fully homomorphic encryption using ideal lattices. Proc. the 41st annual ACM symposium on Theory of Computing, 2009.
3. Gentry, C., Halevi, S.: Implementing Gentry’s fully homomorphic encryption scheme. EUROCRYPT 2011, Springer, 2011.
