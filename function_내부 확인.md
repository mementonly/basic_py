def date_range(
    start=None,
    end=None,
    periods=None,
    freq=None,
    tz=None,
    normalize: bool = False,
    name: Hashable = None,
    inclusive: IntervalClosedType = "both",
    *,
    unit: str | None = None,
    **kwargs,
) -> DatetimeIndex: 
--분석--
 -> DatetimeIndex: 이거는 저 객체형태를 반환한다는 것 
   명칭  type hinting, 즉 타입 힌트
    *,
    unit: str | None = None,
    **kwargs, 
    이 부분은 위치로는 지정이 안되고, 무조건.. 뭐가 뭔지 명확하게 적어야함. 해상도 표현 
    메모리 절약에서 사용 
