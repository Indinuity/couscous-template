# MyCLabs template for Couscous

## Usage

To use the template, set it up in your `couscous.yml` configuration file:

```yaml
template:
    url:
```

## Configuration

Here are all the variables you can set:

```yaml
template:
    github:
        user: hello
        repo: my-project

    title: My project
    subTitle: This is a great project.

    # The left menu bar
    menu:
        sections:
            main:
                name: Main documentation
                items:
                    home:
                        text: Home page
                        # You can use relative urls
                        relativeUrl: doc/faq.html
                    foo:
                        text: Another link
                        # Or absolute urls
                        absoluteUrl: https://example.com
            other:
                name: Other topics
                items:
```
