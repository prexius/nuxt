<template>
    <div>
        <aside>
            <nav>
                <ul>
                    <li>
                        <NuxtLink to="/"> Home </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about"> About </NuxtLink>
                    </li>
                </ul>
            </nav>
        </aside>
        <div>
            <slot />
        </div>
        <footer>
            <p>@Copyright {{new Date().getFullYear()}}</p>
        </footer>
    </div>
</template>