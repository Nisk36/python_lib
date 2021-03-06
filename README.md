[![Netlify Status](https://api.netlify.com/api/v1/badges/372f004b-ea59-4ba2-bbbf-2d5f6213fffd/deploy-status)](https://app.netlify.com/sites/python-2022-lib/deploys)
[![Actions Status](https://github.com/moyomogi/python_2022_lib/actions/workflows/deploy.yml/badge.svg)](https://github.com/moyomogi/python_2022_lib/actions)
[![license](https://img.shields.io/badge/license-CC0--1.0-blue)](https://github.com/moyomogi/python_2022_lib/blob/master/LICENSE)

# ð python_2022_lib

ç«¶æãã­ã°ã©ãã³ã°ç¨ã®ã©ã¤ãã©ãª (Python)  
[Library](https://python-2022-lib.netlify.app/)aa

## localhost ã«ãµã¼ãããæ¹æ³

[Setup digital-garden-with-jekyll](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll) ãåèã«ãã¾ããã

å¿è¦ãªãã¼ã«ãã¤ã³ã¹ãã¼ã« (ååã®ã¿å®è¡ããã°ãã)ã
aa
```sh
# jekyll ã¯ ruby ã§å®è£ããã¦ããã®ã§ ruby ãã¤ã³ã¹ãã¼ã«ã
sudo apt install -y ruby-dev ruby-bundler
gem install jekyll
```

ä»¥ä¸ãå®è¡ããã°ãlib éä¸ã [localhost:4000](http://localhost:4000) ã«ãµã¼ãã§ããã

```sh
# lib éä¸ã®ãã¡ã¤ã«ãåç§ãã
# dist/_notes, dist/_pages éä¸ã« Markdown çæã
python3 generate_notes.py
cd dist

# dist/_notes, dist/_pages éä¸ã®ãã¡ã¤ã«ãåç§ãã
# dist/_site éä¸ã« html ãªã©ãçæã
sudo bundle
# dist/_site éä¸ã®ãã¡ã¤ã«ã
# http://localhost:4000 ã«ãµã¼ãããã
sudo bundle exec jekyll serve
```

## ä½¿ç¨ãããã³ãã¬ã¼ã

[maximevaillancourt/digital-garden-jekyll-template](https://github.com/maximevaillancourt/digital-garden-jekyll-template)

## License

- `docs`, `lib` éä¸ã®ãã¡ã¤ã«ã¯ [CC0](https://creativecommons.org/publicdomain/zero/1.0/deed.ja) ã§è¨±è«¾ããã¦ãã¾ããããªãã¡ãå¼ç¨åã«è¨è¼ããã«ããããã®ãã¡ã¤ã«ã®ä¸é¨ã¾ãã¯å¨é¨ãä½¿ç¨ã§ãã¾ãã
- `dist` éä¸ã®ãã¡ã¤ã«ã¯ãä½¿ç¨ãããã³ãã¬ã¼ã [maximevaillancourt/digital-garden-jekyll-template] ã®ã©ã¤ã»ã³ã¹ã§ãã [MIT](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/LICENSE) ãç¶æ¿ãã¾ããããªãã¡ã`dist` éä¸ã®ãã¡ã¤ã«ã®ä¸é¨ã¾ãã¯å¨é¨ãç¨ããå ´åã¯ [maximevaillancourt/digital-garden-jekyll-template] ãå©ç¨ããæ¨ãè¨è¼ããå¿è¦ãããã¾ãã

[maximevaillancourt/digital-garden-jekyll-template]: https://github.com/maximevaillancourt/digital-garden-jekyll-template
