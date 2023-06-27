<template>
  <div>
    <header>
        <nav>
          <ul>
            <li>
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/events">Events</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/events/222">Event 222</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/events/profile">Events Profile</NuxtLink>
            </li>
          </ul>
        </nav>
      </header>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
