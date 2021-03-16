# Rustlings-Track

This is my mrogress track of [rustlings](https://github.com/rust-lang/rustlings), 🦀 Small exercises to get you used to reading and writing Rust code!

📎 If you are intrested, welcome to try [it](https://github.com/rust-lang/rustlings).

![crab pet](https://i.imgur.com/LbZJgmm.gif)

## Doing exercises

The exercises are sorted by topic and can be found in the subdirectory `rustlings/exercises/<topic>`. For every topic there is an additional README file with some resources to get you started on the topic. We really recommend that you have a look at them before you start.

The task is simple. Most exercises contain an error that keeps them from compiling, and it's up to you to fix it! Some exercises are also run as tests, but rustlings handles them all the same. To run the exercises in the recommended order, execute:

```bash
rustlings watch
```

This will try to verify the completion of every exercise in a predetermined order (what we think is best for newcomers). It will also rerun automatically every time you change a file in the `exercises/` directory. If you want to only run it once, you can use:

```bash
rustlings verify
```

This will do the same as watch, but it'll quit after running.

In case you want to go by your own order, or want to only verify a single exercise, you can run:

```bash
rustlings run myExercise1
```

In case you get stuck, you can run the following command to get a hint for your
exercise:

``` bash
rustlings hint myExercise1
```

## Testing yourself

After every couple of sections, there will be a quiz that'll test your knowledge on a bunch of sections at once. These quizzes are found in `exercises/quizN.rs`.

## Progress-Track

```
✅ variables1
✅ variables2
✅ variables3
✅ variables4
✅ variables5
✅ variables6
✅ functions1
✅ functions2
✅ functions3
✅ functions4
✅ functions5
✅ if1
✅ if2
✅ quiz1
✅ move_semantics1s!
✅ move_semantics2s!
✅ move_semantics3s!
✅ move_semantics4s!
✅ primitive_types1.rs!
✅ primitive_types2.rs!
✅ primitive_types3.rs!
✅ primitive_types4es4.rs
✅ primitive_types5.rs!
✅ primitive_types6es6.rs
✅ structs1
✅ structs2
✅ structs3
✅ enums1
✅ enums2
✅ enums3
✅ modules1
✅ modules2
✅ collections1
✅ collections2
✅ collections3
✅ collections4
✅ strings1
✅ strings2
✅ quiz2
✅ errors1
✅ errors2
✅ errors3
✅ errorsn
✅ generics1
✅ generics2
✅ generics3
✅ option1
✅ option2
✅ result1
✅ traits1
✅ traits2
✅ tests1
✅ tests2
✅ tests3
✅ quiz3
✅ box1s
✅ arc1
✅ iterators11.rs!
✅ iterators2ors2.rs
✅ iterators3ors3.rs
✅ iterators4ors4.rs
✅ threads1
✅ macros1
✅ macros2
✅ macros3
✅ macros4
✅ quiz4
✅ clippy1
✅ clippy2
✅ using_as
✅ from_into
✅ try_from_into
⭕️ as_ref_mut
⭕️ from_str
```

## Thanks ✨

All exercises source from [rustlings](https://github.com/rust-lang/rustlings)