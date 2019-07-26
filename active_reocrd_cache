rails에서의 쿼리 캐시


rails는 기본적으로 하나의 액션에서 동일한 쿼리가 두번 수행시 쿼리를 메모리에 저장해놓고 한번만 수행한다.

``` 
def query_cache_test
   s = StoreOrder.last(2)
   p = StoreOrder.last(2)
```

실제로 이 메소드를 수행시 쿼리는 한번만 수행이 된다.
