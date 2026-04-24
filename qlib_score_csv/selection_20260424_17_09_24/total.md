# params 
 {'predict_dates': [{'start': '2026-04-24', 'end': '2026-04-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260424_16 953181058495054019 (Recorders: 3/5)

	Recorder: d33fe32c16eb45278446fd7a95221952

		Model: {'id': 'd33fe32c16eb45278446fd7a95221952', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.204, 'Rank IC': 0.054, 'Rank ICIR': 0.343}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.343', 'weight': '0.165'}

	Recorder: 524be3226b454a51a26873fd60a50476

		Model: {'id': '524be3226b454a51a26873fd60a50476', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.157, 'Rank IC': 0.018, 'Rank ICIR': 0.144}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.144', 'weight': '0.069'}

	Recorder: e725b82eec38446883ca7c957dd3ed7a

		Model: {'id': 'e725b82eec38446883ca7c957dd3ed7a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.172, 'Rank IC': 0.013, 'Rank ICIR': 0.073}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.073', 'weight': '0.035'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260424_16 993584262367370854 (Recorders: 2/5)

	Recorder: aad86c5cdb78407799472281ba4f74b5

		Model: {'id': 'aad86c5cdb78407799472281ba4f74b5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.26, 'Rank IC': 0.032, 'Rank ICIR': 0.277}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.277', 'weight': '0.133'}

	Recorder: 5aaef6a7b7924661bb2ca7be3f5aca2a

		Model: {'id': '5aaef6a7b7924661bb2ca7be3f5aca2a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.423, 'Rank IC': 0.012, 'Rank ICIR': 0.094}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.094', 'weight': '0.045'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260424_14 630267730660718728 (Recorders: 2/5)

	Recorder: 242173f81bf44a4a9b498fc5d5d66cc6

		Model: {'id': '242173f81bf44a4a9b498fc5d5d66cc6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.026, 'Rank IC': 0.042, 'Rank ICIR': 0.235}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.235', 'weight': '0.113'}

	Recorder: 8206ecb5f5904aafb012942dadb56427

		Model: {'id': '8206ecb5f5904aafb012942dadb56427', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.073, 'Rank IC': 0.013, 'Rank ICIR': 0.112}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.112', 'weight': '0.054'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260424_14 821560091052432170 (Recorders: 2/5)

	Recorder: 94337148c3e3487bb98d281d073cd492

		Model: {'id': '94337148c3e3487bb98d281d073cd492', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.008, 'Rank ICIR': 0.065}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.065', 'weight': '0.031'}

	Recorder: d126755b131049ecbae4bf5471889fc8

		Model: {'id': 'd126755b131049ecbae4bf5471889fc8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.436, 'Rank IC': 0.022, 'Rank ICIR': 0.161}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.161', 'weight': '0.077'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260424_14 387789079445640376 (Recorders: 3/5)

	Recorder: 52bcd0a53cc1435a98ead17cd5f9eb7f

		Model: {'id': '52bcd0a53cc1435a98ead17cd5f9eb7f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.07, 'Rank IC': 0.041, 'Rank ICIR': 0.237}, 'data_train_vec': ['2023-04-24', '2025-07-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.237', 'weight': '0.114'}

	Recorder: 393baa8cbffc4bd682936ff7ddada1f7

		Model: {'id': '393baa8cbffc4bd682936ff7ddada1f7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.111, 'Rank IC': 0.032, 'Rank ICIR': 0.306}, 'data_train_vec': ['2024-04-24', '2025-10-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.306', 'weight': '0.147'}

	Recorder: 1744175fa3be4f42a0e3ba16bd41d459

		Model: {'id': '1744175fa3be4f42a0e3ba16bd41d459', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.25, 'Rank IC': 0.005, 'Rank ICIR': 0.031}, 'data_train_vec': ['2025-04-24', '2026-01-23'], 'train_time_vec': ['2026-04-24', '2026-04-24'], 'rank_icir': '0.031', 'weight': '0.015'}
