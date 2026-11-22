# Physics & Algorithm Experiments

> An interactive laboratory monorepo exploring 2D rigid-body mechanics, collision detection algorithms, projectile trajectories, and particle dynamics built using **Matter.js** and **p5.js**.

[![Play Live Demo](https://img.shields.io/badge/Play-Live%20Demo-38bdf8?style=for-the-badge&logo=google-chrome&logoColor=white)](https://dhruvspatel6113.github.io/physics_and_algorithm_experiments/)

---

## Interactive Lab Catalog

### 1. Collision Algorithms
- **[AABB Intersection](01_collision_algorithms/aabb_intersection/)**: Custom Axis-Aligned Bounding Box intersection algorithm testing rectangular overlaps.
- **[Matter.js Sandbox](01_collision_algorithms/matterjs_collision_sandbox/)**: Collision detection algorithm and boundary bounding box sandbox.

### 2. Ballistics & Impact Deformation
- **[Car Crash Deformation](02_ballistics_and_impact/car_crash_deformation/)**: Kinetic energy dissipation ($E_k = \frac{1}{2}mv^2$) testing deformation against static walls.
- **[Bullet Penetration](02_ballistics_and_impact/bullet_penetration/)**: Material penetration simulation calculating velocity vs. barrier thickness.

### 3. Rigid Body Dynamics & Stability
- **[Matter.js World Setup](03_rigid_body_mechanics/matterjs_world_setup/)**: Gravitational field setup, static ground planes, and restitution coefficients.
- **[Bouncy Ball Restitution](03_rigid_body_mechanics/bouncy_ball_restitution/)**: Elasticity tuning and coefficient of restitution on spheres.
- **[Toppling Boxes Stack](03_rigid_body_mechanics/toppling_boxes_stack/)**: Center-of-mass balance testing on multi-tier block towers.

### 4. Pendulums & Constraints
- **[Newton's Cradle Classic](04_pendulums_and_constraints/newton_cradle_classic/)**: Kinetic energy propagation through suspended steel spheres.
- **[Newton's Cradle 5 Bobs](04_pendulums_and_constraints/newton_cradle_5bobs/)**: Matter.Constraint 5-bob harmonic pendulum simulation.

### 5. Projectile Trajectories
- **[Crumpled Ball Launch](05_projectile_trajectories/crumpled_balls_parabola/)**: Launch impulse with parabolic trajectory and friction.
- **[Paper Ball Trash Toss](05_projectile_trajectories/paper_ball_trash_toss/)**: Toss game with landing boundary detection.

---

## Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/DhruvSPatel6113/physics_and_algorithm_experiments.git
   cd physics_and_algorithm_experiments
   ```
2. Open `index.html` in any browser or launch with:
   ```bash
   npx serve .
   ```
