# loady
Loads webpage with frontend files to calculate page size and load time

Will modify this README later, pretty busy

Example:
```load = Loady( 'https://donjajo.com', headers={ 'User-Agent' : 'Mozilla/5.0 (X11; Fedora; Linux x86_64; rv:57.0) Gecko/20100101 Firefox/57.0' })
load.get()
print( load.total_time ) # Returns total time taken to load all page contents, both css and js
print( load.size ) # Total size of the webpage both css and js
print( load.files ) # Dictionary list of all files and their load time with size
```
