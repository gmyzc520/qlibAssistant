# params 
 {'predict_dates': [{'start': '2026-04-28', 'end': '2026-04-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260428_17 986201827589041342 (Recorders: 3/5)

	Recorder: d11c8a332aaf44d7ac0ff15309e50a01

		Model: {'id': 'd11c8a332aaf44d7ac0ff15309e50a01', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.027, 'Rank ICIR': 0.191}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.191', 'weight': '0.069'}

	Recorder: 405f3ac1e7fe4e2fa6ea4e35007176c5

		Model: {'id': '405f3ac1e7fe4e2fa6ea4e35007176c5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.082, 'Rank IC': 0.017, 'Rank ICIR': 0.169}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.169', 'weight': '0.061'}

	Recorder: 555b34d07e41419d8a383619ee6c5a21

		Model: {'id': '555b34d07e41419d8a383619ee6c5a21', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.288, 'Rank IC': 0.036, 'Rank ICIR': 0.269}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.269', 'weight': '0.097'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260428_17 863708173197589312 (Recorders: 3/5)

	Recorder: 7ec8a7b74e0d4473a684f2682d876a15

		Model: {'id': '7ec8a7b74e0d4473a684f2682d876a15', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.085, 'Rank IC': 0.032, 'Rank ICIR': 0.208}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.208', 'weight': '0.075'}

	Recorder: feba2f784e12416a83d451422aaa39bc

		Model: {'id': 'feba2f784e12416a83d451422aaa39bc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.086, 'Rank IC': 0.013, 'Rank ICIR': 0.118}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.118', 'weight': '0.043'}

	Recorder: 220a1ec41f0946fb9ab0d97d4e93c2ba

		Model: {'id': '220a1ec41f0946fb9ab0d97d4e93c2ba', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.424, 'Rank IC': 0.03, 'Rank ICIR': 0.214}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.214', 'weight': '0.077'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260428_14 890439321724835025 (Recorders: 3/5)

	Recorder: fa7c35098e33484d8e219b135438454b

		Model: {'id': 'fa7c35098e33484d8e219b135438454b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.118, 'Rank IC': 0.048, 'Rank ICIR': 0.283}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.283', 'weight': '0.102'}

	Recorder: 1255172e9783452aa226fe1dcc84ce04

		Model: {'id': '1255172e9783452aa226fe1dcc84ce04', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.044, 'Rank IC': 0.005, 'Rank ICIR': 0.046}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.046', 'weight': '0.017'}

	Recorder: 0fd688f617af4c9b878f60b6a2b23266

		Model: {'id': '0fd688f617af4c9b878f60b6a2b23266', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.218, 'Rank IC': 0.016, 'Rank ICIR': 0.089}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.089', 'weight': '0.032'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260428_14 964111475129543552 (Recorders: 3/5)

	Recorder: 08d54ebf843b4c239704557dd4dcd397

		Model: {'id': '08d54ebf843b4c239704557dd4dcd397', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.029, 'Rank ICIR': 0.246}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.246', 'weight': '0.089'}

	Recorder: 4cd99a6dd3e542358fd435ebbd92518b

		Model: {'id': '4cd99a6dd3e542358fd435ebbd92518b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.009, 'Rank ICIR': 0.075}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.075', 'weight': '0.027'}

	Recorder: d238bc63062348e38c7a5231f8c607a7

		Model: {'id': 'd238bc63062348e38c7a5231f8c607a7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.579, 'Rank IC': 0.043, 'Rank ICIR': 0.328}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.328', 'weight': '0.118'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260428_14 830898930191751076 (Recorders: 3/5)

	Recorder: ba75b49ff2134ff29f1caec20528b3ec

		Model: {'id': 'ba75b49ff2134ff29f1caec20528b3ec', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.018, 'Rank ICIR': 0.102}, 'data_train_vec': ['2021-04-28', '2025-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.102', 'weight': '0.037'}

	Recorder: 2a7e85d4628640589b09e9d58d6aa342

		Model: {'id': '2a7e85d4628640589b09e9d58d6aa342', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.074, 'Rank IC': 0.037, 'Rank ICIR': 0.224}, 'data_train_vec': ['2023-04-28', '2025-07-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.224', 'weight': '0.081'}

	Recorder: ec660f434aaf4a84aa5b9aeb778155aa

		Model: {'id': 'ec660f434aaf4a84aa5b9aeb778155aa', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.075, 'Rank IC': 0.024, 'Rank ICIR': 0.207}, 'data_train_vec': ['2024-04-28', '2025-10-27'], 'train_time_vec': ['2026-04-28', '2026-04-28'], 'rank_icir': '0.207', 'weight': '0.075'}
