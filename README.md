Blank example of a Composer/PSR4 compatibile library.

To use such a library as a part of your project, put the following repository configuration in the composer.json projects file.

```
    "repositories": [
        {
            "type": "path",
            "url": "/path/to/the/library/"
        }
    ],
```
For example, "url": "/home/dev/libs/foobar/"



To use all similar extensions in project, in the projects composer.json file use:

```
    "repositories": [
        {
            "type": "path",
            "url": "/path/to/the/dir/above/library/*"
        }
    ],
```
For example, "url": "/home/dev/libs/*"