# Revision history for vec

## 0.3.0.1

- Fix `product`

## 0.3

- Split `lens` utilities into [`vec-lens`](https://hackage.haskell.org/package/vec-lens) package.
- Add `snoc` and `reverse` operations
- Add `repeat`
- Drop dependency on `base-compat`
- Add explicit `tabulate`

## 0.2

- Add `Data.Vec.DataFamily.SpineStrict.gix`
- Add `Data.Vec.DataFamily.SpineStrict.ix` requires `InlineInduction`

## 0.1.1.1

- Use `fin-0.1`

## 0.1.1

- Add `Data.Vec.DataFamily.SpineStrict` module
- Add `Data.Vec.DataFamily.SpineStrict.Pigeonhole` module:
  this let us define `Representable` in a handy way.

## 0.1

- Reverse dependencies with `boring`.
- GHC-8.4.1 support

## 0

- First version. Released on an unsuspecting world.
