# cantido.github.io

My GitHub.IO web page. Built using [jekyll](https://github.com/jekyll/jekyll).

## To build

1. Install dependencies using `bundle`:

    ```shell
    bundle install
    ```

2. Use Jekyll to build web assets

    ```shell
    jekyll build
    ```

3. Proof the generated HTML:

    ```shell
    bundle exec htmlproofer ./site --disable-external --allow-hash-href
    ```

## License

Copyright © 2016 Rosa Richter. All rights reserved.
