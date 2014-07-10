Packer shell post-processor
=============================

Run shell scripts for post-process images

Usage
-----
Add the post-processor to your packer template:

    {
        "post-processors": [
          {
            "type": "shell",
            "scripts": [
              "script.sh"
            ]
          }
        ]
    }

Available configuration options:



Installation
------------
Run:

    $ go get github.com/vtolstov/packer-post-processor-shell
    $ go install github.com/vtolstov/packer-post-processor-shell

Add the post-processor to ~/.packerconfig:

    {
      "post-processors": {
        "shell": "packer-post-processor-shell"
      }
    }

