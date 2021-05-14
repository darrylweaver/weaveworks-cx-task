# Developer Guide

This readme contains guidance to help setup an environment to complete the task.

## Setup

fork [[GitOps Task]](https://github.com/paulcarlton-ww) or fork it and clone your fork.

### Install Required Software

This project requires the following software:

    [flux](https://toolkit.fluxcd.io/)
    helm
    kubectl
    [kind](https://kind.sigs.k8s.io/docs/)
    kubeseal

You can install these using the 'setup.sh' script:

    scripts/setup.sh

## Task

A script is provided to create a Kind cluster:

    scripts/kind.sh

The scripts directory contains other scripts that you may find useful.
