[kaspresso](../../index.md) / [com.kaspersky.kaspresso.testcases.core.sections](../index.md) / [MainTestSection](index.md) / [init](./init.md)

# init

`fun init(actions: `[`InitData`](index.md#InitData)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`TransformSection`](../-transform-section/index.md)`<`[`Data`](index.md#Data)`>`

Overrides [InitSection.init](../-init-section/init.md)

Can be invoked after [BeforeTestSection](../-before-test-section/index.md). Running to init test data using dsl.

### Parameters

`actions` - actions to be wrapped and invoked before the test.

**Return**
[TransformSection](../-transform-section/index.md) to continue building a test.

