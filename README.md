# konfiguracja środowiska

### instalacja git'a poprzez homebrew

```sh
brew install git
```


### Ulubione komendy z linuxa 5.10.2019
```sh
pwd
ls
mkdir
touch
chmod
cd
mv
```

### tabela

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| 1 | 2 | 3 |
| 1 | 2 | 3 |
| 1 | 2 | 3 |


### Python

```Python
from selenium import webdriver
from selenium.webdriver.common.keys import Keys

driver = webdriver.Firefox()
driver.get("http://www.python.org")
assert "Python" in driver.title
elem = driver.find_element_by_name("q")
elem.clear()
elem.send_keys("pycon")
elem.send_keys(Keys.RETURN)
assert "No results found." not in driver.page_source
driver.close()
```

###logo 
![alt text](https://cdv.pl/wp-content/uploads/2018/02/logo.svg "Logo CDV")


###Video
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
