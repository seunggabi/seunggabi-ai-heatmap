# seunggabi-ai-heatmap

AI usage cost heatmap powered by [ai-heatmap](https://github.com/seunggabi/ai-heatmap).

![AI Heatmap](https://seunggabi.github.io/seunggabi-ai-heatmap/heatmap.svg)

## Usage

```bash
npx --yes ai-heatmap@latest update
```

### Cron (daily update)

```bash
0 0 * * * npx --yes ai-heatmap@latest update
```

## Dynamic SVG (by Vercel)

![AI Heatmap](https://seunggabi-ai-heatmap.vercel.app/api/heatmap?theme=blue)

```bash
npx --yes ai-heatmap@latest deploy
```
