# Menu

Micro services application to save Menu to enjoy the food anytime you need inspiration.

- [React Native](https://facebook.github.io/react-native/)
- [GraphQL](https://graphql.org/)
- [GRPC](https://grpc.io/)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Terraform](https://www.terraform.io/)
- [Kubernetes](https://kubernetes.io/)
- [Linkerd](https://linkerd.io/)
- [Prometheus](https://prometheus.io/)/[Grafana](https://grafana.com/)
- [Skaffold](https://skaffold.dev/)
- [Minikube](https://github.com/kubernetes/minikube)

# Service list

| Service | Language | Description |
| --- | --- | --- |
| [Gateway Service](https://github.com/rodrwan/menu/gateway/) | Golang | This service is intended to be as a joiner of services, act like a bus communicator using graphql to join internal service resposes. |
| [Users Service](https://github.com/rodrwan/menu/users/) | Golang | Stores user information into postgres DB. |
| [Auth Service](https://github.com/rodrwan/menu/auth/) | Golang | Generate a JWT token to access to private resources in the net. |
| [Recipes Service](https://github.com/rodrwan/menu/recipes/) | Golang | Handle recipes, the information are stored in MySQL. |
| [Ingredients Service](https://github.com/rodrwan/menu/ingredients/) | Golang | Save ingredients information, the information are stored in MySQL. |
| [RabbitMQ](https://www.rabbitmq.com/) | - | RabbitMQ is lightweight and easy to deploy on premises and in the cloud. It supports multiple messaging protocols. |

# How to run

TODO.