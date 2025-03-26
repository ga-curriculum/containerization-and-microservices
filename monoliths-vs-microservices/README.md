<h1>
  <span class="headline">Containerization and Microservices</span>
  <span class="subhead">Monoliths vs. Microservices</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to compare and contrast monolithic architectures and microservices architectures, highlighting the key differences in structure, development, deployment, scalability, technology, maintenance, and fault isolation.

## Monoliths vs. microservices

![An application constructed as a monolith vs as a colleciton of microservices.](./assets/monoliths-vs-microservices.png)

Traditionally, applications were built as monoliths. Monoliths are large, complex systems with tightly bound components deployed as a single unit. They are like a big, tangled ball of yarn, where everything is interconnected. Making changes can be challenging if care isn't put into their architecture and organization.

In contrast, microservices architectures break down the application into smaller, loosely coupled services.

Each service has a specific responsibility and can be developed, deployed, and scaled independently. Microservices are organized so that each item has its designated place, and you can easily access and modify them without disrupting the entire system.

Let's compare monoliths and microservices:

| Aspect          | Monoliths                         | Microservices                                        |
| --------------- | --------------------------------- | ---------------------------------------------------- |
| Structure       | Single, tightly coupled           | Loosely coupled, independent services                |
| Development     | Slower, requires coordination     | Faster, autonomous teams                             |
| Deployment      | All or nothing, longer cycles     | Independent, frequent releases                       |
| Scalability     | Scale entire application          | Scale individual services                            |
| Technology      | Limited to a single stack         | Flexibility to choose the best tech for each service |
| Maintenance     | Harder to understand and modify   | Easier to update and maintain                        |
| Fault Isolation | Failure affects the entire system | Failure is isolated to a specific service            |

While monoliths have their place, microservices typically offer a more modular and flexible approach to building applications in today's fast-paced, ever-changing world.
