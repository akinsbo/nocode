# No Code

No code is the best way to write secure and reliable applications. Write nothing; deploy nowhere.

## Infrastructure

**Place diagram here**

When a user first accesses Nocode's URL, he/she hits the load balancer which allows external traffic into the cluster. The load balancer forwards the traffic to the Nginx ingress controller, which then forwards the traffic to either the frontend or the backend depending on the user's request, determined by the URL.

As shown in the diagram, there are two more communications that occur; frontend communicates with the backend and the backend, with the database.

## Getting Started

Start by not writing any code.

```

```

This is just an example application, but imagine it doing anything you want. Adding new features is easy too:

```

```

The possibilities are endless.

### Building the Application

Now that you have not done anything it's time to build your application:

```

```

Yep. That's it. You should see the following output:

```

```

### Deploying

While you still have not done anything it's time to deploy your application. By running the following command you can deploy your application absolutely nowhere.

```

```

It's that simple. And when it comes time to scale the application, all you have to do is:

```

```

I know right?

## Contributing

You don't.
