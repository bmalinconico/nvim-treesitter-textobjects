
### Text objects

You can define text objects based on nodes of the grammar by adding queries in `textobjects.scm`.
Each capture group can be declared as `inner` or `outer`.

```
@attribute.inner
@attribute.outer
@function.inner
@function.outer
@class.inner
@class.outer
@conditional.inner
@conditional.outer
@loop.inner
@loop.outer
@call.inner
@call.outer
@block.inner
@block.outer
@parameter.inner
@parameter.outer

# For LaTeX frames
@frame.inner
@frame.outer
```

Some nodes only have one type:

```
@comment.outer
@statement.outer
@scopename.inner
```
### Automatic README Generation

You don't have to update the support matrix in the README manually.
It's generated by a CI job that runs on pushes to master.

