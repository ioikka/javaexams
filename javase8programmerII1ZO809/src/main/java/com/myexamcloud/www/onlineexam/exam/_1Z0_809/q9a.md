Choice C
========

NullPointerException

Notes
>Optional.of(in[2]).orElse("Empty")

```
/**
 * Returns an {@code Optional} with the specified present non-null value.
 *
 * @param <T> the class of the value
 * @param value the value to be present, which must be non-null
 * @return an {@code Optional} with the value present
 * @throws NullPointerException if value is null
 */
public static <T> Optional<T> of(T value) {
    return new Optional<>(value);
}
```

