def create_readme():
    readme_content = """
    # Project Name

    This is a description of your project.

    ## Installation

    Describe how to install your project.

    ## Usage

    Provide examples or describe how to use your project.

    ## Contributing

    Explain how others can contribute to your project.

    ## License

    Specify the license under which your project is distributed.

    """
    
    with open('README.md', 'w') as f:
        f.write(readme_content)

if __name__ == "__main__":
    create_readme()
