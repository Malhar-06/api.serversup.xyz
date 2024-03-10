# api.serversup.xyz

This project is a fun and collaborative initiative where developers contribute "Hello World" applications in various frameworks. The goal is to showcase different programming languages and frameworks and provide a simple starting point for beginners.
Developers are encouraged to create their own Hello World application in a framework that is not already present on the website. Additionally, to make deployment easier, you're encouraged to create a Docker image of your application. By contributing, you'll not only expand the diversity of frameworks showcased but also provide valuable resources for fellow developers.


## How to Contribute

We welcome contributions from developers of all skill levels. Here's how you can contribute to the project:

1. **Fork the Repository**: Start by forking this repository to your own GitHub account.

2. **Clone the Repository**: Clone the forked repository to your local machine using Git.

    ```bash
    git clone https://github.com/your-username/hello-world-project.git
    ```

3. **Create a New Branch**: Create a new branch named as your user ID for your contributions.

    ```bash
    git checkout -b <your-branch>
    ```
4. **Create your Hello World Application**: You can refer other applications code to create your own application which will give same output as other applications are giving it also includes applications response time.

5. **Add Your Hello World Application**: Add your "Hello World" applocation in the framework of your choice. You need to create a new directory for your application in the ```HelloApps``` directory.

6. **Update some files**: If you're adding a new framework's Dockerimage which is important to show your application on the website, you'll need to modify three files:

* *Nginx Configuration File*: Update the Nginx configuration file ```forconfig/default``` to route traffic to your application. You'll need to add a new location block to proxy requests to your container.

* *Frontend Code*: Modify the ```frontend-code/index.html``` to include a button for your application. This will allow users to easily access your Hello World application from the website.

* *Ansible Playbook*: Update the Ansible playbook ```frameworks.yml``` to include your Docker container image and specify the ports it should expose. This will ensure that your application is properly deployed and accessible.

By making these changes, you'll not only add your Hello World application to the collection but also ensure that it's integrated seamlessly into the project's infrastructure.


7. **Commit Changes**: Commit your changes with descriptive commit messages.

    ```bash
    git commit -am "Add <your-framework> Hello World Application"
    ```

8. **Push Changes**: Push your changes to your forked repository.

    ```bash
    git push origin <your-branch>
    ```

9. **Submit a Pull Request**: Finally, submit a pull request from your branch to the test repository. Be sure to provide a detailed description of your changes.

10. **Review and Merge**: Once your pull request is submitted, it will be reviewed by the project maintainers. If everything looks good, your contribution will be merged into the main branch further in couple of minutes it will be on website.

## Contact

If you have any questions or need further assistance, feel free to reach out to us:

- Project Maintainer: [Malhar](https://github.com/Malhar-06)
- Email: malharchikhale0@gmail.com
- Twitter: [@malhar_chikhale](https://twitter.com/malhar_chikhale)

We appreciate your interest in contributing to the Hello World Project! Happy coding! 🌍👋
