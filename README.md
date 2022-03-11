# [pi库 生态](https://github.com/GaiaWorld/pi_ecosystem)

## [crates.io 的 pi库](https://crates.io/teams/github:gaiaworld:dev)

+ 所有的 crates.io 的 crate 都必须有一个 github 账号 作为 owner
+ 用 GaiaWorld 的 成员 账号 登录 crates.io 生成 token
+ 本地命令行 cargo login token
+ 为项目 加入 dev-团队 作为 owner，以便于 可以在一个组内看到所有的crates
    - cargo owner --add github:GaiaWorld:dev
+ cargo publish

## 领域库

### 前端领域

+ [pi_ecs](https://github.com/GaiaWorld/pi_ecs)
+ [pi_show](https://github.com/GaiaWorld/pi_show)
+ [pi_math](https://github.com/GaiaWorld/pi_math)
+ [pi_render](https://github.com/GaiaWorld/pi_render)
+ [pi_msdf_tool](https://github.com/GaiaWorld/pi_msdf_tool)

### 服务器端

+ [pi_crypto](https://github.com/GaiaWorld/pi_crypto)
+ [pi_vm](https://github.com/GaiaWorld/pi_vm)
+ [pi_store](https://github.com/GaiaWorld/pi_store)
+ [pi_db](https://github.com/GaiaWorld/pi_db) 
+ [pi_net](https://github.com/GaiaWorld/pi_net)

## 不再维护的 crates

+ [pi_lib](https://github.com/GaiaWorld/pi_lib)
+ [pi_sys](https://github.com/GaiaWorld/pi_sys)
+ [pi_p2p](https://github.com/GaiaWorld/pi_p2p)
+ [pi_base](https://github.com/GaiaWorld/pi_base)
+ [pi_front](https://github.com/GaiaWorld/pi_front)
+ [pi_tools](https://github.com/GaiaWorld/pi_tools)
+ [pi_serv](https://github.com/GaiaWorld/pi_serv)
+ 基础库
  - [pi_adler32](https://github.com/GaiaWorld/pi_adler32)
  - [pi_bincode](https://github.com/GaiaWorld/pi_bincode)
  - [pi_data_view](https://github.com/GaiaWorld/pi_data_view)
  - [pi_ecs_derive_old](https://github.com/GaiaWorld/pi_ecs_derive_old)
  - [pi_ecs_old](https://github.com/GaiaWorld/pi_ecs_old)
  - [pi_flex_layout_old](https://github.com/GaiaWorld/pi_flex_layout_old)
  - [pi_hashmap](https://github.com/GaiaWorld/pi_hashmap)
  - [pi_idtree_old](https://github.com/GaiaWorld/pi_idtree_old)
  - [pi_map_old](https://github.com/GaiaWorld/pi_map_old)
  - [pi_slab_old](https://github.com/GaiaWorld/pi_slab_old)
  - [pi_fx_hashmap](https://github.com/GaiaWorld/pi_fx_hashmap)
  - [pi_wy_hash](https://github.com/GaiaWorld/pi_wy_hash)
  - [pi_task_pool](https://github.com/GaiaWorld/pi_task_pool)

## 基础库

+ baip
    - [pi_timer](https://github.com/GaiaWorld/pi_timer)
+ zhuy
    - [pi_file](https://github.com/GaiaWorld/pi_file)
    - [pi_weight_task](https://github.com/GaiaWorld/pi_weight_task)
+ luob
    - [pi_time](https://github.com/GaiaWorld/pi_time)
    - [pi_gray](https://github.com/GaiaWorld/pi_gray)
    - [pi_guid](https://github.com/GaiaWorld/pi_guid)
    - [pi_guid64](https://github.com/GaiaWorld/pi_guid64)
    - [pi_compress](https://github.com/GaiaWorld/pi_compress)
+ zuon
    - [pi_apm](https://github.com/GaiaWorld/pi_apm)
    - [pi_async](https://github.com/GaiaWorld/pi_async)
    - [pi_async_file](https://github.com/GaiaWorld/pi_async_file)
    - [pi_async_macro](https://github.com/GaiaWorld/pi_async_macro)
    - [pi_future](https://github.com/GaiaWorld/pi_future)
    - [pi_handler](https://github.com/GaiaWorld/pi_handler)
    - [pi_js_proxy_gen](https://github.com/GaiaWorld/pi_js_proxy_gen)
    - [pi_js_proxy_gen_macro](https://github.com/GaiaWorld/pi_js_proxy_gen_macro)
    - [pi_lfstack](https://github.com/GaiaWorld/pi_lfstack)
    - [pi_worker](https://github.com/GaiaWorld/pi_worker)
+ moyy
    - [pi_graph](https://github.com/GaiaWorld/pi_graph)
    - [pi_async_graph](https://github.com/GaiaWorld/pi_async_graph)
+ suncy
    + [pi_densevec](https://github.com/GaiaWorld/pi_densevec)
    + [pi_ordmap](https://github.com/GaiaWorld/pi_ordmap)
    + [pi_any](https://github.com/GaiaWorld/pi_any)
    + [pi_atom](https://github.com/GaiaWorld/pi_atom)
    + [pi_base58](https://github.com/GaiaWorld/pi_base58)
    + [pi_bon](https://github.com/GaiaWorld/pi_bon)
    + [pi_cancel_timer](https://github.com/GaiaWorld/pi_cancel_timer)
    + [pi_compress](https://github.com/GaiaWorld/pi_compress)
    + [pi_cowlist](https://github.com/GaiaWorld/pi_cowlist)
    + [pi_cross_performance](https://github.com/GaiaWorld/pi_cross_performance)
    + [pi_debug_info](https://github.com/GaiaWorld/pi_debug_info)
    + [pi_deque](https://github.com/GaiaWorld/pi_deque)
    + [pi_dirty](https://github.com/GaiaWorld/pi_dirty)
    + [pi_dyn_uint](https://github.com/GaiaWorld/pi_dyn_uint)
    + [pi_enum_default_macro](https://github.com/GaiaWorld/pi_enum_default_macro)
    + [pi_ext_heap](https://github.com/GaiaWorld/pi_ext_heap)
    + [pi_flex_layout](https://github.com/GaiaWorld/pi_flex_layout)
    + [pi_hash](https://github.com/GaiaWorld/pi_hash)
    + [pi_hash_value](https://github.com/GaiaWorld/pi_hash_value)
    + [pi_heap](https://github.com/GaiaWorld/pi_heap)
    + [pi_idtree](https://github.com/GaiaWorld/pi_idtree)
    + [pi_listener](https://github.com/GaiaWorld/pi_listener)
    + [pi_local_timer](https://github.com/GaiaWorld/pi_local_timer)
    + [pi_lru](https://github.com/GaiaWorld/pi_lru)
    + [pi_map](https://github.com/GaiaWorld/pi_map)
    + [pi_null](https://github.com/GaiaWorld/pi_null)
    + [pi_pointer](https://github.com/GaiaWorld/pi_pointer)
    + [pi_res](https://github.com/GaiaWorld/pi_res)
    + [pi_res_mgr](https://github.com/GaiaWorld/pi_res_mgr)
    + [pi_rsync](https://github.com/GaiaWorld/pi_rsync)
    + [pi_share](https://github.com/GaiaWorld/pi_share)
    + [pi_sinfo](https://github.com/GaiaWorld/pi_sinfo)
    + [pi_slab](https://github.com/GaiaWorld/pi_slab)
    + [pi_slot_deque](https://github.com/GaiaWorld/pi_slot_deque)
    + [pi_slot_wheel](https://github.com/GaiaWorld/pi_slot_wheel)
    + [pi_static_map](https://github.com/GaiaWorld/pi_static_map)
    + [pi_ucd](https://github.com/GaiaWorld/pi_ucd)
    + [pi_util](https://github.com/GaiaWorld/pi_util)
    + [pi_weight](https://github.com/GaiaWorld/pi_weight)
    + [pi_wheel](https://github.com/GaiaWorld/pi_wheel)
    + [pi_wtree](https://github.com/GaiaWorld/pi_wtree)
    + [pi_wy_rng](https://github.com/GaiaWorld/pi_wy_rng)

## 附录：内部项目 【内网 GitLab 中】

#### js

+ [pi_sys](http://192.168.31.241:10082/tech/pi_sys)
+ [pi_build](http://192.168.31.241:10082/tech/pi_build)
+ [pi_utils](http://192.168.31.241:10082/tech/pi_utils)
+ [pi_pt](http://192.168.31.241:10082/tech/pi_pt)
+ [pi_commom](http://192.168.31.241:10082/tech/pi_common)
+ [pi_packer](http://192.168.31.241:10082/tech/pi_packer)
+ [pi_animation](http://192.168.31.241:10082/tech/pi_animation)

#### rust

+ [pi_ai](http://192.168.31.241:10082/tech/pi_ai)
+ [pi_animation_rust](http://192.168.31.241:10082/tech/pi_animation_rust)
+ [pi_logger](http://192.168.31.241:10082/tech//pi_logger)
+ [pi_v8](http://192.168.31.241:10082/tech/pi_v8)
+ [pi_serv](http://192.168.31.241:10082/tech/pi_serv)
+ [pi_serv_lib](http://192.168.31.241:10082/tech/pi_serv_lib)
+ [pi_serv_builtin](http://192.168.31.241:10082/tech/pi_serv_builtin)
+ [pi_serv_ext](http://192.168.31.241:10082/tech/pi_serv_ext)
+ [pi_core](http://192.168.31.241:10082/tech/pi_core)
+ [pi_core_lib](http://192.168.31.241:10082/tech/pi_core_lib)
+ [pi_core_builtin](http://192.168.31.241:10082/tech/pi_core_builtin)

#### 其他

+ [pi_android](http://192.168.31.241:10082/tech/pi_android)
+ [pi_ios](http://192.168.31.241:10082/tech/pi_ios)
