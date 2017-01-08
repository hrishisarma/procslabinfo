# procslabinfo
Routine prototype: void my_get_kmalloc_cache_slabinfo(void)
Definition location: source/mm/slub.c
Declaration location: source/include/linux/slab.h
Call location:
Kernel_init( )
{
……
flush_delayed_fput();
my_get_kmalloc_cache_slabinfo();
……
}
