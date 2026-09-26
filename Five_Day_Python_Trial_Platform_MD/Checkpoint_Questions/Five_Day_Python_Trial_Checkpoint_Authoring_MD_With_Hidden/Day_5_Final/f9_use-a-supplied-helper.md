# F9 — Use a Supplied Helper

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Checkpoint | Day 5 Final Coding Checkpoint |
| Day | 5 |
| Classification | Core |
| Raw marks | 10 |
| Language | Python |

## Task

Complete `order_cost` by calling `pack_cost` and adding `delivery_fee`.

## Starter Code

```python
def pack_cost(quantity, unit_price):
    return quantity * unit_price

def order_cost(quantity, unit_price, delivery_fee):
    pass
```

## Allowed Keywords / Constructs

- function call to `pack_cost`
- `+`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing `pack_cost`
- duplicating helper logic instead of calling `pack_cost`

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `order_cost(4, 150, 100)` | `700` |
| `order_cost(0, 150, 80)` | `80` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `order_cost(2, 500, 0)` | `1000` |
| `order_cost(3, 125, 25)` | `400` |
| `order_cost(1, 999, 1)` | `1000` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
