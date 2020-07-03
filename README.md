# Stubhub-Microservices-and-Event-Streaming
5 microservices in Typescript to: authenticate users, handle ticketing requests, process orders, handle payments using Stripe API and an expiration microservice with a Redis cache store. Used NATS Streaming server to facilitate asynchronous communication between all microservices. Created deployments for Kubernetes cluster for all 5 express microservices and their MongoDB instances. Built error handling abstractions for error communication and tested all services using Jest and Supertest.
