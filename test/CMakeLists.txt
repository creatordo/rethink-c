add_library(testcases alloc-testing.c test_helper.c test_arraylist.c test_list.c
                 test_queue.c test_bitmap.c test_matrix.c 
                 test_bstree.c test_avltree.c test_rbtree.c test_heap.c test_skip_list.c
                 test_bignum.c test_dijkstra.c test_prime.c test_hash_table.c
                 test_kmp.c test_bm.c test_sunday.c test_trie.c test_ac.c test_text.c
                 test_huffman.c test_distance.c test_vector.c)
target_compile_options(testcases PRIVATE ${COMPILE_OPTIONS})
target_include_directories(testcases PRIVATE ${INCLUDE_DIRECTORIES})
