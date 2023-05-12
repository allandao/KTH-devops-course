# Assignment Proposal

## Title

Single Tenant vs Multi-Tenant SaaS Demo

## Names and KTH ID

  - Minh Allan Dao (madao@kth.se)
  - Moritz Lübken (mlubken@kth.se)

## Deadline

- Week 7

## Category

- Presentation

## Description

Many well known applications are "multi-tenant". That means there is only one "instance" of this application, serving all the users at the same time.

However, especially in the B2B world, there are very good reasons to completely separate the data of your customers.

This can result in a so called single tenant architecture, where every customer (tenant) has their own instance of a piece of software deployed (such as software you are offering).

We will look at the differences between single and multi tenant systems, especially the pros and cons.
Then we will demonstrate an example of how to implement a multi-tenant system for small scale applications using Docker, Portainer and a self-build portal to subscribe to application offerings.

**Relevance**

We can simplify, automate, and better secure the deployment of single tenant applications through our standard set of DevOps processes and practices. This helps to ensure that the CI/CD experience is more streamlined and consistent for all tenants, regardless of how they are subscribed. With this in mind, we seek to demo how we might actually implement one form of tenancy (multi) to share what developers need to do to establish this model.

**Readings**
- https://learn.microsoft.com/en-us/azure/architecture/isv/application-tenancy
- https://www.digitalguardian.com/de/blog/saas-single-tenant-vs-multi-tenant-whats-difference

**Contributors**

@mlubken, @allandao