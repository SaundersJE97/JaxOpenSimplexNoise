# JaxOpenSimplex
OpenSimplex Written in Jax

# Usage
```python
seed, _ = jax.random.split(jax.random.PRNGKey(seed=0))

x = jnp.array([2_000, 2_000])
y = jnp.array([-3_000, -3_000])
z = jnp.array([5_000, 5_000])
t = jnp.array([180, 180])
noise = Simplex2Jax4d.noise4_Fallback(seed, x, y, z, t)
```

# Installation
## Using Pip
```bash
pip install JaxOpenSimplexNoise
```
## From Source
```bash
cd <dir>
git clone https://github.com/SaundersJE97/JaxOpenSimplexNoise.git
export PYTHONPATH = $PYTHONPATH:<dir>/JaxOpenSimplexNoise:
```

# Todo
| Task                          | Status |
|-------------------------------|--------|
| Implement 1d                  | ⬜ |
| Implement 2d                  | ⬜ |
| Implement 3d                  | ⬜ |
| Implement 4d                  | ✅ |
| Add Tests and Benchmarks      | ⬜ |

# Other cool JAX Libraries
