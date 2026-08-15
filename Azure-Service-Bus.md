# Azure Service Bus

#azure #messaging #interview

## Overview

Azure Service Bus is a cloud-based messaging broker used for asynchronous communication.

## Why Use It?

- Decouples applications
- Reliable delivery
- Supports retries
- Supports transactions

## Components

### Queue

One producer -> One consumer

### Topic

One producer -> Multiple subscribers

## Architecture

```mermaid
flowchart LR

ApplicationA --> ServiceBus
ServiceBus --> ApplicationB
