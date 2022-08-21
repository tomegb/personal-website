<template>
	<div class="navbar bg-base-200">
		<div class="navbar-start">
			<a class="btn btn-ghost text-xl normal-case">apis</a>
			<div class="navbar-start">
				<div class="dropdown">
					<label tabindex="0" class="btn btn-ghost btn-circle">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="h-5 w-5"
							fill="none"
							viewBox="0 0 24 24"
							stroke="currentColor"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M4 6h16M4 12h16M4 18h7"
							/>
						</svg>
					</label>
					<ul
						tabindex="0"
						class="dropdown-content menu rounded-box menu-compact mt-3 w-52 bg-base-100 p-2 shadow"
					>
						<li><a>Home</a></li>
						<li><a>Features</a></li>
						<li><a>Commands</a></li>
						<li><a>Support</a></li>
					</ul>
				</div>
			</div>
		</div>
		<div class="navbar-end">
			<div class="dropdown dropdown-end">
				<label tabindex="0" class="avatar btn btn-ghost btn-circle">
					<div class="w-10 rounded-full">
						<img src="" />
					</div>
				</label>
				<ul
					tabindex="0"
					class="dropdown-content menu rounded-box menu-compact mt-3 w-52 bg-base-100 p-2 shadow"
				>
					<li>
						<a class="justify-between">
							Profile
							<span class="badge">New</span>
						</a>
					</li>
					<li><a>Settings</a></li>
					<li><a>Logout</a></li>
				</ul>
			</div>
		</div>
	</div>
</template>
