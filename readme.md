# per-time
A small tool for working with Web Performance API.

## Installation

```bash
$ yarn add per-time
```

## Usage

Get measurements:

```javascript
timing.getNavigationDuration();
```

![](./snapshot-duration.png)

Get paint timing:

```javascript
timing.getPaintTiming();
```

Make a table:

```javascript
timing.table();
```

![](./snapshot-table.png)

## License

MIT