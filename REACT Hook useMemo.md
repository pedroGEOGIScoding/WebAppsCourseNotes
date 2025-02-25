# REACT

Class: FRONTEND

Notes: Hook useMemo

The hook useMemo is a React Hook that lets you cache the result of a calculation between re-renders. Usually it is used to save cache between renders with processes or intensive calculations to optimize performance in expensive computations. So, useMemo is used for **memorization**, a technique to optimize performance by caching the results of expensive computations.

```jsx
const cachedValue = useMemo(calculateValue, dependencies)
```

This optimization is particularly useful for avoiding unnecessary re-renders in components. It’s commonly employed for computationally intensive tasks, like complex calculations or data processing, where you want to avoid redundant work. By memorizing values, useMemo helps improve React application efficiency and responsiveness.