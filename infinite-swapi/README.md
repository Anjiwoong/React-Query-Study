# section 03

- React Query를 이용한 무한 스크롤 기능
- pageParam 배열은 가져와야 할 다음 페이지를 나타내는데 getNextPageParam 옵션을 통해 관리되며 두 가지 매개변수를 사용한다.
- lastPage나 allPages가 옵션이고 API에서 반환된 데이터 양식에 따라 고르면 된다.
- pageParam은 또 hasNextPage 값을 제어하는데 이 불리언 값은 pageParam이 정의되어 있으면 참 그리고 정의되지 않았으면 거짓을 반환해서 더 불러올 데이터가 있는지 확인할 수 있다.
- fetchNextPage는 컴포넌트의 영향을 받기 때문에 컴포넌트가 데이터를 불러와야 할 때를 결정하고 hasNextPage 프로퍼티로 데이터를 그만 가져오게 할 수 있다.
