## Flow

To consume a query as a Flow, depend on the Coroutines extensions artifact and use the extension method it provides:

=== "Kotlin"
    ```kotlin
    dependencies {
      implementation("app.cash.sqldelight:coroutines-extensions:{{ versions.sqldelight }}")
    }
    ```
=== "Groovy"
    ```groovy
    dependencies {
      implementation "app.cash.sqldelight:coroutines-extensions:{{ versions.sqldelight }}"
    }
    ```

{% include 'common/coroutines-usage.md' %}
