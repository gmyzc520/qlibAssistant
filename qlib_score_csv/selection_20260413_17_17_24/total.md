# params 
 {'predict_dates': [{'start': '2026-04-13', 'end': '2026-04-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260413_16 353305167734691906 (Recorders: 3/5)

	Recorder: 53d52ae151714c64914fe78974de09d2

		Model: {'id': '53d52ae151714c64914fe78974de09d2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.28, 'Rank IC': 0.046, 'Rank ICIR': 0.316}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.316', 'weight': '0.089'}

	Recorder: ce1ed8dc1df24e73bd9bf125e0c0f836

		Model: {'id': 'ce1ed8dc1df24e73bd9bf125e0c0f836', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.224, 'Rank IC': 0.051, 'Rank ICIR': 0.411}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.411', 'weight': '0.116'}

	Recorder: b6c8a011cffc473c80feeef99fab0b05

		Model: {'id': 'b6c8a011cffc473c80feeef99fab0b05', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.362, 'Rank IC': 0.043, 'Rank ICIR': 0.345}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.345', 'weight': '0.097'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260413_16 495158823384808891 (Recorders: 2/5)

	Recorder: a13fbc0750c846f2ae4c1b078fe27814

		Model: {'id': 'a13fbc0750c846f2ae4c1b078fe27814', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.108, 'Rank IC': 0.017, 'Rank ICIR': 0.141}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.141', 'weight': '0.040'}

	Recorder: 49d27591fc9944b584587ecb565e0a14

		Model: {'id': '49d27591fc9944b584587ecb565e0a14', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.203, 'Rank IC': 0.036, 'Rank ICIR': 0.223}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.223', 'weight': '0.063'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260413_14 635928525936009235 (Recorders: 4/5)

	Recorder: 239712da197241b794f342f2030a6248

		Model: {'id': '239712da197241b794f342f2030a6248', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.021, 'Rank ICIR': 0.125}, 'data_train_vec': ['2021-04-13', '2025-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.125', 'weight': '0.035'}

	Recorder: 514f0192ed694fec880071d193e3ae21

		Model: {'id': '514f0192ed694fec880071d193e3ae21', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.098, 'Rank IC': 0.047, 'Rank ICIR': 0.264}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.264', 'weight': '0.074'}

	Recorder: 04602086bc5c47ef9315950a08ca4058

		Model: {'id': '04602086bc5c47ef9315950a08ca4058', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.129, 'Rank IC': 0.023, 'Rank ICIR': 0.193}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.193', 'weight': '0.054'}

	Recorder: cd9c2c62657f4c3cb0ddd1d106c1e71e

		Model: {'id': 'cd9c2c62657f4c3cb0ddd1d106c1e71e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.111, 'Rank IC': 0.016, 'Rank ICIR': 0.091}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.091', 'weight': '0.026'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260413_14 694683403179352304 (Recorders: 4/5)

	Recorder: be46cbac57964629a53a0a5e40555401

		Model: {'id': 'be46cbac57964629a53a0a5e40555401', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.063, 'Rank IC': 0.018, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-04-13', '2025-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.160', 'weight': '0.045'}

	Recorder: c4d3484741de4c64b0d8c069c17e3733

		Model: {'id': 'c4d3484741de4c64b0d8c069c17e3733', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.1, 'Rank IC': 0.037, 'Rank ICIR': 0.321}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.321', 'weight': '0.090'}

	Recorder: 9187eef277c248d299a7ddd1c6000086

		Model: {'id': '9187eef277c248d299a7ddd1c6000086', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.115, 'Rank IC': 0.02, 'Rank ICIR': 0.172}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.172', 'weight': '0.048'}

	Recorder: 385c4ab35b2e45df9aefdc3c49ef9a9b

		Model: {'id': '385c4ab35b2e45df9aefdc3c49ef9a9b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.2, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.138', 'weight': '0.039'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260413_14 908474298689877301 (Recorders: 3/5)

	Recorder: 4944621d284b47a38ee7238aac4ac654

		Model: {'id': '4944621d284b47a38ee7238aac4ac654', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.124, 'Rank IC': 0.037, 'Rank ICIR': 0.226}, 'data_train_vec': ['2023-04-13', '2025-07-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.226', 'weight': '0.064'}

	Recorder: 89c4d5585abd48838418984b17d00743

		Model: {'id': '89c4d5585abd48838418984b17d00743', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.161, 'Rank IC': 0.041, 'Rank ICIR': 0.351}, 'data_train_vec': ['2024-04-13', '2025-10-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.351', 'weight': '0.099'}

	Recorder: 6dd8361132244ba5a94cfd326612eea0

		Model: {'id': '6dd8361132244ba5a94cfd326612eea0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.121, 'Rank IC': 0.012, 'Rank ICIR': 0.076}, 'data_train_vec': ['2025-04-13', '2026-01-12'], 'train_time_vec': ['2026-04-13', '2026-04-13'], 'rank_icir': '0.076', 'weight': '0.021'}
