## Java의 Exception 종류

1. Checked Exception: 컴파일 시점에서 확인되는 예외, 반드시 처리 필요 (IOException, SQLException 등).
2. Unchecked Exception: 런타임에서 발생, 컴파일러가 강제하지 않음 (NullPointerException, ArithmeticException 등).
3. Error: 시스템 레벨에서 발생하는 심각한 오류, 복구 불가 (OutOfMemoryError, StackOverflowError 등).
## @Valid
Spring과 Java Bean Validation에서 객체 검증에 사용되는 애노테이션으로, 컨트롤러나 서비스에서 요청 객체의 유효성 검사에 활용.