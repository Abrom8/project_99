<template>
  <div class="hero min-h-screen">
    <div class="flex-col justify-center hero-content">
      <div class="text-center lg:text-left">
        <h1 class="mb-5 text-5xl font-bold">Body data input</h1>
      </div>
      <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
        <div class="card-body">
          <div class="form-control">
            <label class="label">
              <span class="label-text">Weight</span>
            </label>
            <input
              type="number"
              step="0.1"
              placeholder="kg"
              class="input input-bordered"
            />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Bodyfat %</span>
            </label>
            <input
              type="number"
              step="0.1"
              placeholder="%"
              class="input input-bordered"
            />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Muscle %</span>
            </label>
            <input
              type="number"
              step="0.1"
              placeholder="%"
              class="input input-bordered"
            />
          </div>
          <div class="form-control">
            <label class="label">
              <span class="label-text">Visceral Fat</span>
            </label>
            <input
              type="number"
              placeholder="10"
              class="input input-bordered"
            />
          </div>

          <div class="form-control mt-6">
            <input type="button" value="Save" class="btn btn-primary" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
