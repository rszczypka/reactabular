7.1.0 / 2016-xx-xx
==================

  * Bug fix - Make sure search `input`s get an empty default value to avoid a React warning about converting from an uncontrolled component to a controlled one.

6.0.0 / 2016-10-14
==================

  * Bug fix - Make toggling behavior rely on `property` over `id`. Now the behavior is more consistent with filtered sets. #216
  * Bug fix - If `column.property` is not set, generate key based on column index instead.

1.2.4 / 2016-08-08
==================

  * Improvement - Rewrite as a stateless function. You should pass `query` as a prop now.

1.2.3 / 2016-08-08
==================

  * Initial release.
