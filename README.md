# dotnet SDK for RISC-V

This project builds the .NET SDK for the `riscv64` architecture and makes the binary files available for distribution. The compiled .NET binaries are then used to build the [GitHub Actions runner for RISC-V](https://github.com/RISC-V-Runners/github-actions-riscv), enabling CI/CD workflows on RISC-V infrastructure.

## About

The .NET SDK binaries built by this project are essential components for the RISC-V GitHub Actions runner, allowing developers to run .NET applications and build processes on RISC-V64 architecture within their CI/CD pipelines.

> **Free CI/CD Minutes Available!** Get 3000 free minutes/month of CI/CD jobs at [www.riscvrunners.com](https://www.riscvrunners.com)

## Build Process

This project was created with help from the [PowerPC64LE build scripts](https://github.com/ppc64le/build-scripts/blob/master/d/dotnet7/dotnet-build-ppc64le), adapted for the RISC-V64 architecture.
