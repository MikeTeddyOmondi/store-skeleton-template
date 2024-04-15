<script>
	import { Avatar } from '@skeletonlabs/skeleton';
	import { ShoppingCart } from 'lucide-svelte';
</script>

<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container p-4 mx-auto flex justify-center items-center">
	<div class="space-y-10 text-center flex flex-col items-center">
		<div class="card grid grid-cols-[auto_1fr_auto] items-center w-full">
			<div class="snap-x snap-mandatory scroll-smooth flex overflow-x-auto">
				<img
					class="snap-center rounded-container-token"
					src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&dpr=1"
					alt=""
					loading="lazy"
				/>
			</div>
		</div>

		<div class="w-full text-token grid grid-cols-1 md:grid-cols-3 gap-4">
			<a class="card card-hover overflow-hidden" href="/">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h3 class="h3" data-toc-ignore>Product one</h3>
					<article></article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>Rating</h6>
						<button type="button" class="btn variant-filled">
							<span><ShoppingCart /></span>
							<!-- <span>Add to Cart</span> -->
						</button>
					</div>
				</footer>
			</a>
			<a class="card card-hover overflow-hidden" href="/elements/cards">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h6 class="h6" data-toc-ignore>Announcements</h6>
					<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
					<article>
						<p>
							<!-- cspell:disable -->
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet
							eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam iure molestias
							cum expedita architecto itaque quae rem.
							<!-- cspell:enable -->
						</p>
					</article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>By Alex</h6>
						<small>On {new Date().toLocaleDateString()}</small>
					</div>
				</footer>
			</a>
			<a class="card card-hover overflow-hidden" href="/elements/cards">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h6 class="h6" data-toc-ignore>Announcements</h6>
					<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
					<article>
						<p>
							<!-- cspell:disable -->
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet
							eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam iure molestias
							cum expedita architecto itaque quae rem.
							<!-- cspell:enable -->
						</p>
					</article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>By Alex</h6>
						<small>On {new Date().toLocaleDateString()}</small>
					</div>
				</footer>
			</a>
			<a class="card card-hover overflow-hidden" href="/">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h6 class="h6" data-toc-ignore>Announcements</h6>
					<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
					<article>
						<p>
							<!-- cspell:disable -->
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet
							eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam iure molestias
							cum expedita architecto itaque quae rem.
							<!-- cspell:enable -->
						</p>
					</article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>By Alex</h6>
						<small>On {new Date().toLocaleDateString()}</small>
					</div>
				</footer>
			</a>
			<a class="card card-hover overflow-hidden" href="/elements/cards">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h6 class="h6" data-toc-ignore>Announcements</h6>
					<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
					<article>
						<p>
							<!-- cspell:disable -->
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet
							eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam iure molestias
							cum expedita architecto itaque quae rem.
							<!-- cspell:enable -->
						</p>
					</article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>By Alex</h6>
						<small>On {new Date().toLocaleDateString()}</small>
					</div>
				</footer>
			</a>
			<a class="card card-hover overflow-hidden" href="/elements/cards">
				<header>
					<img
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb&w=1024&h=768&dpr=1"
						class="bg-black/50 w-full aspect-[21/9]"
						alt="Post"
						loading="lazy"
					/>
				</header>
				<div class="p-4 space-y-4">
					<h6 class="h6" data-toc-ignore>Announcements</h6>
					<h3 class="h3" data-toc-ignore>Skeleton is Awesome!</h3>
					<article>
						<p>
							<!-- cspell:disable -->
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam aspernatur provident eveniet
							eligendi cumque consequatur tempore sint nisi sapiente. Iste beatae laboriosam iure molestias
							cum expedita architecto itaque quae rem.
							<!-- cspell:enable -->
						</p>
					</article>
				</div>
				<hr class="opacity-50" />
				<footer class="p-4 flex justify-start items-center space-x-4">
					<Avatar
						src="https://images.pexels.com/photos/3861969/pexels-photo-3861969.jpeg?auto=compress&cs=tinysrgb"
						width="w-8"
					/>
					<div class="flex-auto flex justify-between items-center">
						<h6 class="font-bold" data-toc-ignore>By Alex</h6>
						<small>On {new Date().toLocaleDateString()}</small>
					</div>
				</footer>
			</a>
		</div>
	</div>
</div>

<style lang="postcss">
	img {
		width: 100%;
		height: 100%;
		object-fit: cover;
	}
</style>
